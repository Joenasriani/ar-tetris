## AR Tetris 3D

Play AR Tetris in your browser using WebXR.

Go to: https://joenasriani.github.io/ar-tetris/

### Supported Devices
Mobile (Android Chrome with ARCore) and Meta Quest Browser only.
iOS Safari does not support WebXR hit-test.

### Audio
Background music: `music/music-rock.mp3`
Sound effects: `music/tik.mp3`, `music/outro.mp3`, `music/lineclear.mp3`

### Recording
Video recording uses the `MediaRecorder` + `captureStream` APIs.
These are **not supported** in all browsers (notably iOS Safari and some WebXR contexts).
If recording is unavailable, an on-screen message will be displayed.

### Local Development
Serve the root folder with any HTTPS-capable static server, e.g.:
```
npx serve .
```
WebXR and media capture APIs require a secure context (HTTPS or localhost).
