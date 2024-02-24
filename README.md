# Auth-Flutter-Firebase

A comprehensive Flutter project demonstrating the use of Firebase Authentication to implement email and password sign-in functionality. This project builds upon a modern login UI to integrate Firebase for authentication, allowing users to sign in with their email and password.

### Key Features

- Modern, clean login and registration UI.
- Email and password authentication using Firebase.
- User authentication state management with StreamBuilder.
- Error handling for login and registration processes.
- Loading indicators for asynchronous operations.

## Getting Started

To get this project up and running on your local machine, follow these steps.

### Prerequisites

Ensure you have the following installed before proceeding:
- Flutter SDK
- An IDE with Flutter support (e.g., VSCode, Android Studio)
- Firebase CLI

### Installation

1. **Clone the Repository**

   ```sh
   git clone https://github.com/Raunak-Sarmacharya/Auth-Flutter-Firebase.git

### Setup

1. **Firebase Configuration**: Ensure you have a Firebase project set up and configured. You'll need to configure the Firebase SDK with your project's details. Follow the [Firebase documentation](https://firebase.google.com/docs) to create a new project, disable Google Analytics for simplicity, and add your app to Firebase.
   
2. **Firebase CLI**: Install the Firebase CLI using npm or any method suitable for your development environment. This is crucial for integrating Firebase services into your Flutter app.

    ```bash
    npm install -g firebase-tools
    ```

4. **FlutterFire Configuration**: Use the `flutterfire configure` command to automatically configure your Flutter app with Firebase. This step will update your `build.gradle` files and add necessary Firebase dependencies to your project.

6. **Sign-In Method**: Enable Email/Password as a sign-in method in your Firebase project's Authentication section.

### Running the Project

Once setup is complete Install Dependencies, run the Flutter app:

```bash
flutter pub get
```
```bash
flutter run
