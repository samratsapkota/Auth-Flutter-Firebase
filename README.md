# Auth-Flutter-Firebase

A comprehensive Flutter project demonstrating the use of Firebase Authentication to implement email and password sign-in functionality. This project builds upon a modern login UI to integrate Firebase for authentication, allowing users to sign in with their email and password.

## Features

- Modern login UI.
- Firebase Authentication integration.
- Email and password sign-in.
- User state management with StreamBuilder.
- Error handling and loading indicators for a better user experience.

## Getting Started

### Prerequisites

- Flutter installed on your system.
- Firebase project created and configured.
- Firebase CLI installed.

### Setup

1. **Firebase Configuration**: Ensure you have a Firebase project set up and configured. Follow the [Firebase documentation](https://firebase.google.com/docs) to create a new project, disable Google Analytics for simplicity, and add your app to Firebase.

2. **Firebase CLI**: Install the Firebase CLI using npm or any method suitable for your development environment. This is crucial for integrating Firebase services into your Flutter app.

    ```bash
    npm install -g firebase-tools
    ```

3. **FlutterFire Configuration**: Use the `flutterfire configure` command to automatically configure your Flutter app with Firebase. This step will update your `build.gradle` files and add necessary Firebase dependencies to your project.

4. **Dependencies**: Add `firebase_core` and `firebase_auth` to your `pubspec.yaml` file. This can be done manually or through the terminal as shown in the tutorial.

    ```bash
    flutter pub add firebase_core
    flutter pub add firebase_auth
    ```

5. **Sign-In Method**: Enable Email/Password as a sign-in method in your Firebase project's Authentication section.

6. **Code Integration**: Follow the tutorial to integrate Firebase authentication into your Flutter app. This includes initializing Firebase in your `main.dart`, creating a login page, and handling user sign-in and sign-out.

### Running the Project

Once setup is complete, run your Flutter app:

```bash
flutter run
