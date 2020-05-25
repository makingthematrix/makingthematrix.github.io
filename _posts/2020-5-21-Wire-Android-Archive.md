---
layout: post
title: Wire Android Archive
published: true
---
Due to recent changes, for some time now the only official channel of distribution for new releases  of Wire Android will be Google Play Store. I decided this is a good opportunity to set up an archive of APKs which you can download and install without having anything to do with Google - except for that apks are stored on Google Drive. I will try  my best to keep this website up to date with the newest releases unless I have good reasons to skip some (e.g. if I know that a hotfix is coming soon). 

Please note this is an **unofficial** channel of distribution. 

### How to install an APK?

My favourite method is with [adb](https://developer.android.com/studio/command-line/adb). Download it, install it, connect your phone and make sure it's allowed to install apps on it through USB. Then go to the console and type:
```
> adb devices
List of devices attached
[device id]	device
```

This is to make sure your phone is connected. If it is, type:
```
> adb install -r -d /[path to downloaded APK]/wire-prod-release-[release number].apk 
```

You can read more [here](https://www.xda-developers.com/quickly-install-adb/).
Or if you don't want to use `adb` you can try [other methods](https://www.lifewire.com/install-apk-on-android-4177185).


## Wire Android 3.48.915


Download: [link](https://drive.google.com/open?id=1qJaWusjulqVq3Og01_-bUfXduOXuGfyi)

Released on: 2020-05-13

SHA256: dafa14ac066e6c49ef4545251dbbcbf2b2f39d46523779e923308d2702e4a1b0

Release notes: [Main release](https://github.com/wireapp/wire-android/releases/tag/3.48) + [hotfix](https://github.com/wireapp/wire-android/releases/tag/3.48.915)
