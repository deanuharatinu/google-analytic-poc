# google_analytic_poc

Project for Proof Of Concept (POC) of implementing Firebase Analytics a.k.a Google Analytics

## Getting Started

Install the Firebase CLI

Installation on MacOS
1. Run the following cURL command to download Firebase CLI tools:
    ```
    curl -sL https://firebase.tools | bash
    ```
2. Log in to Firebase using CLI:
    ```
    firebase login
    ```
3. Test that CLI is properly installed:
    ```
    firebase projects:list
    ```
4. Install the FlutterFire CLI by running the following command from any directory:
    ```
    dart pub global activate flutterfire_cli
    ```
5. From your flutter project directory, configure your apps to use Firebase
    ```
    flutterfire configure
    ```
6. From your Flutter project directory, run the following command to install the core plugin:
    ```
    flutter pub add firebase_core
    ```
7. From your Flutter project directory, install Firebase Analytics using the following command:
    ```
    flutter pub add firebase_analytics
    ```

## Enable DebugView
DebugView enables you to see the raw event data logged by your app on development devices in near real-time.

- for Android:
    ```
    adb shell setprop debug.firebase.analytics.app <<android-package-name>>
    ```
