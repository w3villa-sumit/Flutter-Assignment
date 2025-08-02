🚀 Flutter User Registration Form
✨ Overview
A sleek and responsive Flutter app featuring a user registration form with real-time validation. Collects user info for Name, Email, Password, and Confirm Password — designed for a smooth signup experience! 🎉

🔥 Features
📝 Input Fields with Validation:

👤 Name: At least 3 characters

📧 Email: Valid email format using regex

🔒 Password: Minimum 6 characters

🔑 Confirm Password: Must match Password

⚡ Real-time Validation:

Instant feedback with clear error messages below each field ❗

🛠️ Form Management:

Powered by GlobalKey<FormState> for reliable validation control

🎯 Submit Button:

Disabled until all fields are valid ✔️

Shows a 🎉 “Registration Successful” snackbar on success

🎨 User Interface:

Clean, modern layout with outlined text fields ✍️

Responsive design for all screen sizes 📱💻

📋 Prerequisites
🛠️ Flutter SDK (3.0.0 or above recommended)

💻 Dart SDK (2.17.0 or above)

🧰 IDE with Flutter support (VS Code, Android Studio, etc.)

🚀 Installation
Clone or download the repo.

Verify Flutter is installed:

bash
Copy
Edit
flutter doctor
Navigate to the project folder and install dependencies:

bash
Copy
Edit
flutter pub get
Run the app on your emulator or device:

bash
Copy
Edit
flutter run
📁 File Structure
lib/main.dart — Contains the full registration form implementation

🎯 Usage
Launch the app.

Fill out the form:

👤 Enter Name (min 3 characters)

📧 Enter a valid Email (e.g., user@example.com)

🔒 Enter Password (min 6 characters)

🔑 Confirm Password (must match Password)

The Register button becomes enabled ✅ once all inputs are valid.

Tap Register:

✅ Shows 🎉 Registration Successful snackbar if all is good

❌ Otherwise, displays helpful error messages below fields

📦 Dependencies
Flutter Material Components (bundled with Flutter SDK)

📝 Notes
Uses TextFormField for all inputs with built-in validation

Email checked with regex for correct format ✔️

Submit button disabled (greyed out) until form is valid

Controllers are disposed properly to prevent memory leaks 🧹

Built with Flutter’s Material Design principles for smooth UX

📜 License
This project is licensed under the MIT License — feel free to use, modify, and share! 👐
