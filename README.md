# Signal Android for BlackBerry OS 10.3 [![Release](https://img.shields.io/badge/release-v3.13.1%2Bbb10u2-blue.svg)](https://github.com/cosmomill/Signal-Android/releases/latest)

Signal is a messaging app for simple private communication with friends.

Signal uses your phone's data connection (WiFi/3G/4G) to communicate securely, optionally supports plain SMS/MMS to function as a unified messenger, and can also encrypt the stored messages on your phone.

## Installation Prerequisites ![BlackBerry 10.3.2.2836 tested](https://img.shields.io/badge/BlackBerry-10.3.2.2836%20tested-brightgreen.svg)

To use voice calls in Signal you need to install [microG](https://microg.org/) GmsCore. If you have already installed [Cobalt's Google Apps](http://forums.crackberry.com/android-apps-amazon-store-apk-files-f413/cobalts-official-google-apps-landing-page-965257/), you have to uninstall Google Account Manager, Blackberry Google ID and Google Play services before proceeding to install [microG](https://microg.org/) GmsCore. 
- Download and install [microG Services Core v0.2.1](https://microg.org/fdroid/repo/com.google.android.gms-8489296.apk).
- Download and install [BlankStore v0.7.5](https://github.com/mar-v-in/BlankStore/releases/download/v0.7.5/BlankStore.apk).
- Make sure you have valid login credentials for a Google Account.
- Generate a Android ID by following [these steps](http://forum.xda-developers.com/showpost.php?p=42983611&postcount=306).
- Open the _System Settings_, tap _Accounts_ then tap _Add Account_ and choose _Market_ enter your login, password and Android ID. The other fields don't need to be changed. Tap _Create Account_ and you're done.
- Open the microG Settings app and tick both checkboxes to enable services such as Google Cloud Messaging.
- Restart your BlackBerry!

## WebSocket Support

This branch adds rudimentary WebSocket-ONLY support to Signal Private Messenger. In order to build a modified version of libtextsecure is needed, for that checkout [this](https://github.com/JavaJens/libtextsecure-java/tree/fix/maven_local) repository.

## Contributing Bug reports

We use GitHub for bug tracking. Please search the existing issues for your bug and create a new one if the issue is not yet tracked!

https://github.com/cosmomill/Signal-Android/issues

# Legal things
## Cryptography Notice

This distribution includes cryptographic software. The country in which you currently reside may have restrictions on the import, possession, use, and/or re-export to another country, of encryption software.
BEFORE using any encryption software, please check your country's laws, regulations and policies concerning the import, possession, or use, and re-export of encryption software, to see if this is permitted.
See <http://www.wassenaar.org/> for more information.

The U.S. Government Department of Commerce, Bureau of Industry and Security (BIS), has classified this software as Export Commodity Control Number (ECCN) 5D002.C.1, which includes information security software using or performing cryptographic functions with asymmetric algorithms.
The form and manner of this distribution makes it eligible for export under the License Exception ENC Technology Software Unrestricted (TSU) exception (see the BIS Export Administration Regulations, Section 740.13) for both object code and source code.

## License

Copyright 2011 Whisper Systems

Copyright 2013-2016 Open Whisper Systems

Licensed under the GPLv3: http://www.gnu.org/licenses/gpl-3.0.html
