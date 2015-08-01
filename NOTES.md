# NOTES #
Date: 2015-03-16

## Docs ##

https://github.com/apache/cordova-plugin-splashscreen/

## Reference for config.xml ##

https://github.com/phonegap/phonegap-start/blob/master/www/config.xml

## Sizes ##

https://github.com/phonegap/phonegap/wiki/App-Splash-Screen-Sizes

## BUGS ##
Date: 2015-07-16
Updated: 2015-08-01

*PhoneGap 3.6 and Icon Path Issues #522
* https://github.com/phonegap/phonegap-cli/issues/522
* Mar 20 2015 - This issue mostly affects Phonegap CLI and not so much Build 

*UNSUPPORTED: Platform element is not supported - #445 - Feature Request*
* https://github.com/phonegap/build/issues/445
* June 2015 - Windows 8 needs better support

*[Docs] Fix Icons and Splash Screens src relative path - #388*
* https://github.com/phonegap/build/issues/388
* December 2014

*Config.xml preferences are PhoneGapBuild only or obsolete - #151*
* https://github.com/phonegap/phonegap-start/issues/151
* June 2014

*Incorrect config.xml Global Preferences - CB-6182*
* https://issues.apache.org/jira/browse/CB-6182
* March 2014
* 2 of 3 related bugs fixed, fix include 'orientation' - April 2014

----
Date: 2015-06-07
Landscape not working on several iOS devices. It seems to be as much because those sizes are not described in either the documentation nor the example ''config.xml'' provide by phonegap.

http://docs.phonegap.com/en/3.3.0/config_ref_images.md.html#Icons%20and%20Splash%20Screens
https://github.com/phonegap/phonegap-start/blob/master/www/config.xml

The issue is shallowly reported.
http://community.phonegap.com/nitobi/topics/pgb-3-6-3-miss-the-following-ioss-splash-screen-size
http://community.phonegap.com/nitobi/topics/landscapes-splashscreen-in-iphone-6-plus-ios-8-1-is-out-of-shape
https://github.com/phonegap/build/issues/411
https://issues.apache.org/jira/browse/CB-8272 (cordova)

----
Date: 2015-03-16
* did not work on first try, documentation on phonegap is incomplete

phonegap dont show splashscreen
http://stackoverflow.com/questions/25156326/phonegap-dont-show-splashscreen

Phonegap Build App Don't Display Splash Screen in Android [solved]
http://stackoverflow.com/questions/25007228/phonegap-build-app-dont-display-splash-screen-in-android-solved/25009015#25009015

"Subjective Effect" seems to have found the answer.
[code]
<gap:splash src="splash.png" />
[/code]
is required. 2015-03-16T23:04:55 - Yeah. It worked. That was dumb.


SEE: Android for "gap:qualifier"
http://developer.android.com/guide/topics/resources/providing-resources.html
