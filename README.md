# react-native-camera-megapixel

This package is to find out the Camera Megapixel of android device in React Native📱.

# Usage

```javascript
import CameraMP from './CameraMP';

CameraMP.getBackCameraResolutionInMp(
(res) => {
    alert(res + 'mp Camera');
},
(err) => {
    alert('err ' + err);
},
);
`
```
