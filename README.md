
Go to:
>> https://joenasriani.github.io/ar-tetris/

## Device & Browser Support

| Platform | AR (WebXR) | Recording |
|---|---|---|
| Android Chrome | ✅ Supported | ✅ Supported |
| Meta Quest Browser | ✅ Supported | ⚠️ May be unavailable in immersive mode |
| iOS Safari | ❌ WebXR not supported | ❌ Not supported |

> **Note on Recording:** In-page video recording uses `MediaRecorder` + `captureStream`. These APIs are not available in all WebXR contexts (e.g., Meta Quest Browser in immersive mode, iOS). If recording is unsupported, the app will display a brief message and reset the button instead of throwing an error. Use the device's built-in screen recorder as an alternative on unsupported platforms.
