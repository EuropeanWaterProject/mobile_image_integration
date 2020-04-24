# Mobile App Code  (HTML, CSS, JS and WebRTC) for integrating single snap photos into Mapillary - very beta

Code adapted from the following github scripts and contributors
Camera capture code :
https://github.com/kasperkamperman/MobileCameraTemplate
[Kasper Kamperman](https://www.kasperkamperman.com/blog/camera-template/)
Exif Editing
Hiroaki Matoba
https://github.com/hMatoba/piexifjs
https://blog.hmatoba.net/


### Requirements

- WebRTC is only supported on secure connections. So you need to serve it from https. 
*You can test and debug in Chrome from localhost though (this doesn't work in Safari).* 

- A recent OS and browser. It should work on recent Phones and OS-es. If it isn't, please 
  let me know (issue) (including a suggestion to fix it). Also add the debugging info in the console.

### Functionalities

- Fullscreen mode (not on Safari mobile (iOS))
- Take Photo
- Flip Camera (environment / user)
- Supports both portrait and landscape mode



## Created/(Adapted from other people's code) by 

Stuart Rapoport
https:europeanwaterproject.org

## Good WebRTC resources

- https://webrtc.github.io/samples/
- https://www.webrtc-experiment.com/
- https://www.html5rocks.com/en/tutorials/getusermedia/intro/
- https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia
