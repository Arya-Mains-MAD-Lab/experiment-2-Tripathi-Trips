# Flutter Login App

## Overview

This project is a simple Flutter-based login application. It demonstrates basic user authentication using hardcoded credentials and navigation between screens.

The app contains a login screen where users enter a username and password. If the credentials are correct, the user is redirected to a home screen displaying a success message. Otherwise, an error message is shown.

---

## Features

* User input fields for username and password
* Password masking using secure input
* Basic authentication logic (hardcoded)
* Navigation between login and home screen
* Error handling using SnackBar

---

## Technologies Used

* Flutter
* Dart
* Material UI components

---

## Project Structure

* `main.dart`

  * Contains the entire application logic
  * Includes:

    * `MyApp`: Root widget
    * `LoginPage`: Handles user login
    * `HomePage`: Displays success message

---

## How It Works

1. The app starts with the `LoginPage`.
2. User enters:

   * Username
   * Password
3. On clicking the Login button:

   * If username is `admin` and password is `1234`, user is navigated to the HomePage.
   * Otherwise, a SnackBar displays "Invalid Credentials".

---

## How to Run

1. Install Flutter on your system.
2. Create a new Flutter project or place this code in `main.dart`.
3. Run the following command:

   ```
   flutter run
   ```
4. Launch the app on an emulator or physical device.

---

## Future Improvements

* Replace hardcoded credentials with secure authentication
* Add form validation
* Implement API-based login
* Improve UI/UX design
* Add persistent login using local storage

---

## Student Information

* Name: Sidharth Tripathi
* Roll Number: 23EACCA047
* Branch: Al
* Batch: BETA
