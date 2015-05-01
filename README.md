# Phonegap-Splashscreen-Test
A simple test of Phonegaps's Splash Screen API.

[table]
! Implemented Platforms
Android
iOS
[/table]

[table]
! Supported Platforms | Yes (X), No (-) or Quirk (Q)
Amazon Fire OS | X
Android | X
BlackBerry 10 | Q
iOS | Q
Windows Phone 7 and 8 | X
Windows 8 | X
[/table]

'''CLI and API'''
From: http://docs.phonegap.com/en/3.3.0/cordova_splashscreen_splashscreen.md.html#Splashscreen

'''config.xml'''
From: https://github.com/phonegap/phonegap-start/blob/master/www/config.xml
[code]
<gap:splash src="res/screen/android/screen-ldpi-portrait.png" gap:platform="android" gap:qualifier="port-ldpi" />
<gap:splash src="res/screen/android/screen-mdpi-portrait.png" gap:platform="android" gap:qualifier="port-mdpi" />
<gap:splash src="res/screen/android/screen-hdpi-portrait.png" gap:platform="android" gap:qualifier="port-hdpi" />
<gap:splash src="res/screen/android/screen-xhdpi-portrait.png" gap:platform="android" gap:qualifier="port-xhdpi" />

<gap:splash src="res/screen/ios/screen-iphone-portrait.png" gap:platform="ios" width="320" height="480" />
<gap:splash src="res/screen/ios/screen-iphone-portrait-2x.png" gap:platform="ios" width="640" height="960" />
<gap:splash src="res/screen/ios/screen-iphone-portrait-568h-2x.png" gap:platform="ios" width="640" height="1136" />
<gap:splash src="res/screen/ios/screen-ipad-portrait.png" gap:platform="ios" width="768" height="1024" />
<gap:splash src="res/screen/ios/screen-ipad-landscape.png" gap:platform="ios" width="1024" height="768" />
[/code]


=== Known Issues ===
Phonegap calls these "Quirks".

[table]
! Supported Platforms | Quirk
BlackBerry 10 | The config.xml file's AutoHideSplashScreen setting must be false. 
iOS | The config.xml file's AutoHideSplashScreen setting must be false. To delay hiding the splash screen for two seconds, add a timer such as the following in the deviceready event handler:
[/table]
