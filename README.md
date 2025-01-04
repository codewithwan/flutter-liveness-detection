# Face Detection Android App

This app uses **Google ML Kit Face Detection** to detect faces in images or through the camera in real-time. The app also manages device permissions such as camera, storage, and internet access.

---

## 📋 Features
- **Face Detection**: Detects facial features such as eyes, nose, mouth, and pose.
- **Compatibility**: Supports images from storage or camera capture.
- **Real-time Processing**: Real-time face detection through the camera.

---

## 🛠️ Setup and Installation

### 1. Add Permissions in AndroidManifest.xml
Ensure the app has the following permissions:

```xml
<uses-permission android:name="android.permission.CAMERA"/>
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>
<uses-permission android:name="android.permission.INTERNET"/>
```

### 2. Add Dependency
Add the **ML Kit Face Detection** dependency in the `build.gradle` file at the app level:

```gradle
dependencies {
    implementation 'com.google.mlkit:face-detection:16.1.7'
}
```

---

## 🚀 How to Use
1. Clone this repository to your Android Studio project.
2. Ensure all permissions are set in the `AndroidManifest.xml` file.
3. Add face detection code using the ML Kit API in the main application file.
4. Run the app on a device or emulator with a supported camera.

---

## 📝 Additional Documentation
For more information about the ML Kit Face Detection API, visit the [official ML Kit documentation](https://developers.google.com/ml-kit/vision/face-detection).

---

## 🛡️ Required Permissions
- **Camera**: To capture images directly.
- **Storage**: To save and read image files.
- **Internet**: (Optional) If there is a need for online connectivity.

---

## 🔧 Contribution
If you would like to contribute, please fork this repository and submit a pull request. All contributions are greatly appreciated!

---
