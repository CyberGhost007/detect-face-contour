# Face Contour Detection and Heart Rate Monitoring App

Face Contour Detection and Heart Rate Monitoring App! This app utilizes advanced computer vision techniques to detect face contours and leverages your smartphone's camera and flashlight to monitor your heart rate.

## Features

- **Face Contour Detection**: Detects and highlights the contours of your face in real-time using your device's camera.
- **Heart Rate Monitoring**: Measures your heart rate using the camera and flashlight by analyzing the changes in the color of your fingertip.

## Screenshots

<p align="center">
  <img src="https://github.com/CyberGhost007/detect-face-contour/assets/29411278/7df8fc3a-aa97-4c4d-a802-0dc724f9531b" width="25%" />
  <img src="https://github.com/CyberGhost007/detect-face-contour/assets/29411278/ae23d1cd-b2c9-4277-a871-882de5fcdd33" width="25%" />
    <img src="https://github.com/CyberGhost007/detect-face-contour/assets/29411278/739ab68b-b22c-4707-9b2f-21dcecbf5f0c" width="25%" />
</p>

<p align="center">
  <img src="https://github.com/CyberGhost007/heartBPM/assets/29411278/873a5eff-acfe-42cb-a527-a48e0ee910a5" width="25%" />
  <img src="https://github.com/CyberGhost007/heartBPM/assets/29411278/aaf0d9e8-d597-4d43-9284-46247fa84438" width="25%" />
  <img src="https://github.com/CyberGhost007/detect-face-contour/assets/29411278/6c42fbfa-f817-443d-92bc-b7af2af85482" width="25%" />
  
</p>

## Installation

To get started with the app, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/CyberGhost007/detect-face-contour.git
    cd detect-face-contour
    ```

2. **Install dependencies**:
    Ensure you have Flutter installed on your system. Then, run:

    ```bash
    flutter pub get
    ```

3. **Run the app**:

    ```bash
    flutter run
    ```

## Usage

1. **Face Contour Detection**:
    - Open the app and navigate to the Face Contour Detection screen.
    - Allow the app to access your camera.
    - Point the camera towards your face, and the app will highlight the contours of your face in real-time.

2. **Heart Rate Monitoring**:
    - Open the app and navigate to the Heart Rate Monitoring screen.
    - Place your finger on the camera lens and cover it completely.
    - The app will use the flashlight to illuminate your finger and analyze the changes in color to calculate your heart rate.

## Dependencies

This app uses the following Flutter packages:

- [camera](https://pub.dev/packages/camera): For accessing the device camera.
- [google_ml_kit](https://pub.dev/packages/google_mlkit_face_detection): For face contour detection.
- [wakelock](https://pub.dev/packages/wakelock): To keep the screen on during heart rate monitoring.
