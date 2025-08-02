Flutter User Registration Form

Overview

This project implements a simple user registration form in Flutter with input validation. The form includes fields for name, email, password, and confirm password, with a submit button that enables only when all fields are filled.

Features





Input Fields:





Name (minimum 3 characters)



Email (valid email format)



Password (minimum 6 characters)



Confirm Password (must match password)



Validation:





Real-time validation with error messages displayed below each field



Form managed using GlobalKey<FormState>



Submit Button:





Enabled only when all fields contain input



Shows a "Registration Successful" snackbar on valid submission



UI:





Clean layout with outlined text fields



Proper spacing and responsive design

Prerequisites





Flutter SDK (version 3.0.0 or higher recommended)



Dart (version 2.17.0 or higher)



Any IDE with Flutter support (e.g., VS Code, Android Studio)

Installation





Clone or download the project repository.



Ensure Flutter is installed. Run flutter doctor to verify setup.



Navigate to the project directory and run:

flutter pub get



Run the app:

flutter run

File Structure





lib/main.dart: Contains the main application code with the registration form implementation.

Usage





Launch the app on an emulator or physical device.



Fill in the form fields:





Name: Enter at least 3 characters.



Email: Enter a valid email address (e.g., user@example.com).



Password: Enter at least 6 characters.



Confirm Password: Must match the password field.



The "Register" button enables only when all fields are filled.



Press the "Register" button to validate the form.



On successful validation, a snackbar displays "Registration Successful".



If validation fails, error messages appear below the respective fields.

Dependencies





Flutter Material Components (included with Flutter SDK)

Notes





The form uses TextFormField widgets for all inputs.



Email validation uses a regex pattern to ensure proper format.



The submit button is disabled (greyed out) until all fields have input.



Controllers are properly disposed of to prevent memory leaks.



The app is built with a responsive design using Flutter's Material Design.

License

This project is open-source and available under the MIT License.
