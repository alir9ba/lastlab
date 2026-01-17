# Device Features App

## Student Information
* **Name:** Alireza Bagheri
* **Student ID:** 210408910

## Project Overview
This is a React Native application built for Lab 7: Accessing Native Device Features. [cite_start]The app demonstrates the use of Expo APIs to interact with hardware features including the camera, gallery, location services, local notifications, and haptic feedback [cite: 7, 34-40].

## Features
* [cite_start]**Camera & Gallery:** Take photos or pick images from the device gallery [cite: 35-36].
* [cite_start]**Location:** Fetch the device's current GPS coordinates[cite: 38].
* [cite_start]**Notifications:** Trigger local notifications upon successful location retrieval[cite: 39].
* [cite_start]**Haptics:** Provide tactile feedback during user interactions[cite: 40].

## Setup Instructions
[cite_start]To run this project locally, follow these steps[cite: 30]:

1.  **Clone the repository**
    ```bash
    git clone <YOUR_REPO_URL>
    cd DeviceFeaturesApp
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Start the application**
    ```bash
    npx expo start
    ```

4.  **Run on Device**
    * Scan the QR code using the **Expo Go** app on your physical device (Android/iOS).
    * Or press `a` for Android Emulator / `i` for iOS Simulator.

## Dependencies
* `expo-camera`
* `expo-image-picker`
* `expo-location`
* `expo-notifications`
* `expo-haptics`
* `@react-navigation/native` & `@react-navigation/native-stack`
