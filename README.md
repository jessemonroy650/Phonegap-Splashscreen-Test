# Phonegap-Splashscreen-Test
A simple test of Phonegaps's Splash Screen API.

**Platforms Implemented Here**
* Android
* iOS


Supported Platforms | Yes (X), No (-) or Quirk (Q)
--------------------|-----------------------------
Amazon Fire OS | X 
Android | X
BlackBerry 10 | Q
iOS | Q
Windows Phone 7 and 8 | X
Windows 8 | X

#### CLI and API ####
From: http://docs.phonegap.com/en/3.3.0/cordova_splashscreen_splashscreen.md.html#Splashscreen

#### config.xml ####
From: https://github.com/phonegap/phonegap-start/blob/master/www/config.xml

### Known Issues ###
Phonegap calls these "Quirks".

Platforms | Quirk
----------|------
BlackBerry 10 | The config.xml file's AutoHideSplashScreen setting must be false.
iOS | The config.xml file's AutoHideSplashScreen setting must be false. To delay hiding the splash screen for two seconds, add a timer such as the following in the deviceready event handler:

