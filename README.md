# react-native-camera-megapixel

This package is to find out the Camera Megapixel of android device in React Native📱.

## Screenshot

<img src="./screenshots/screenshot.jpeg" alt='screenshot' height="300px" width="150px"/>

## Dependency

Add the following permission in AndroidManifest

```javascript
<uses-permission android:name="android.permission.CAMERA" />
```

## Usage

```javascript
import CameraMP from "react-native-camera-megapixel";

CameraMP.getBackCameraResolutionInMp(
  (res) => {
    alert(res + "mp Camera");
  },
  (err) => {
    alert("err " + err);
  }
);
```

## Referance

https://stackoverflow.com/questions/6952469/determining-camera-resolution-i-e-megapixels-programmatically-in-android
