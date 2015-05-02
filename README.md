# Phonegap-Splashscreen-Test
A simple test of Phonegaps's Splash Screen API.

Phonegap Reference

http://plugins.cordova.io/#/package/org.apache.cordova.splashscreen

**Platforms Implemented Here**
* Android (Sizes:200x320-ldpi, 320x480-mdpi, 480x800-hdpi, 720x1280-xhdpi)
* iOS (iPhone 320x480-portrait, 640x960-portrait,  640x1136-portrait)
* iOS (iPad 768x1024-portrait, 1024x768-landscape)
* **NOTE** I have not tested all sizes.

####Reference for iOS devices and screen sizes####
http://www.idev101.com/code/User_Interface/launchImages.html

####On filesnames and how they are found for iOS####
http://drekka.github.io/2012/07/30/iOS-icons-and-splash-screens.html

This article suggests your can give the images any filename you want. When I finally got mine to work, I tested that. The answer is: *Yes you can name the images any filename you want.* My iPodTouch had an actual pixel size of 640x1136.

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

