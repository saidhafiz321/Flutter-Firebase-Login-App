 Flutter Firebase Login App
 
This Flutter project demonstrates a simple login application using Firebase Authentication. Users can log in using their email and password, and upon successful login, they are directed to a profile screen.

Getting Started
Prerequisites
Before running the app, make sure you have Flutter and Dart installed on your system. Also, ensure that you have a Firebase project set up.

Installation
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/saidhafiz321/flutter-firebase-login.git
Navigate to the project directory:

bash
Copy code
cd flutter-firebase-login
Run the following command to get the dependencies:

bash
Copy code
flutter pub get
Firebase Configuration
Create a new Firebase project on the Firebase Console.
Set up Firebase Authentication with the Email/Password sign-in method.
Download the google-services.json file and place it in the android/app directory for Android or the GoogleService-Info.plist file in the ios/Runner directory for iOS.
Usage
Open the project in your preferred Flutter development environment (e.g., Visual Studio Code, Android Studio).

Run the app on an emulator or physical device:

bash
Copy code
flutter run
Test the app with the following credentials:

Email: usertest@gmail.com
Password: user123
Features
User authentication with Firebase Authentication.
Login screen with email and password fields.
Simple error handling for unsuccessful login attempts.
Profile screen navigation upon successful login.
Troubleshooting
If you encounter any issues, ensure that you have followed the Firebase configuration steps correctly and have the required dependencies installed.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Flutter
Firebase
Feel free to contribute, report issues, or provide feedback to help improve this project!