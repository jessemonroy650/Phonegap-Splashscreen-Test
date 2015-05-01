# Phonegap-Splashscreen-Test
A simple test of Phonegaps's Splash Screen API.

**Platforms Implemented Here**
* Android (Sizes:200x320-ldpi, 320x480-mdpi, 480x800-hdpi, 720x1280-xhdpi)
* iOS (iPhone 320x480-portrait, 640x960-portrait-2x,  640x1136-portrait-568h-2x
* iOS (iPad 768x1024-portrait, 1024x768-landscape)
**NOTE** I have not tested all sizes.

Phonegap Supported Platforms | Yes (X), No (-) or Quirk (Q)
--------------------|-----------------------------
Amazon Fire OS | X 
Android | X
BlackBerry 10 | Q
iOS | Q
Windows Phone 7 and 8 | X
Windows 8 | X

#### CLI and API ####
From: https://github.com/apache/cordova-plugin-splashscreen/

#### config.xml ####
From: https://github.com/phonegap/phonegap-start/blob/master/www/config.xml

### Known Issues ###
Phonegap calls these "Quirks".

Platforms | Quirk
----------|------
BlackBerry 10 | The config.xml file's AutoHideSplashScreen setting must be false.
iOS | The config.xml file's AutoHideSplashScreen setting must be false. SEE Documents for more details.

