# Cordova Plugin - Camera Permission

Cordova / PhoneGap Plugin to explicitly ask for permission to use camera and photo library



This plugin simply modifies the Info.plist of your cordova application to include

`NSCameraUsageDescription` and `NSPhotoLibraryUsageDescription`.



This will prompt the user for permission to use the camera and the library when he clicks on a `file` input.



## Installation

- `cordova plugin add https://github.com/Michelemassari/cordova-plugin-camera-permission#0.1.0 —save`
- `cordova platform rm ios && cordova platform add ios`



## Supported Platforms

iOS



## License

[MIT](https://opensource.org/licenses/MIT)



## Author

Made with ❤️ by [Mike Massari](http://michelemassari.net) in 2017