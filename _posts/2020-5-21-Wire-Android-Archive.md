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

## Wire Android 3.50.922


Download: [link](https://drive.google.com/file/d/1GRcpTMVjYYEuFj3fOvvJj6X1GhQ0hbGJ)

Released on: 2020-06-11

SHA256: f90419a7f530083a85f2dfc6438f5d0f101914ace53037038cecf48a65826d26

Release notes: [Main release](https://github.com/wireapp/wire-android/releases/tag/3.50)

## Wire Android 3.49.918


Download: [link](https://drive.google.com/file/d/116XWP4ZY7gJu9RsQMlX1cjnMdkvHCV2U)

Released on: 2020-05-28

SHA256: 9c95014c5b08ff8b33625a4604416c83864a4a8644aefa972498bab67d4583a9

Release notes: [Main release](https://github.com/wireapp/wire-android/releases/tag/3.49) + [hotfix](https://github.com/wireapp/wire-android/releases/tag/3.49.918)

## Wire Android 3.48.915


Download: [link](https://drive.google.com/open?id=1qJaWusjulqVq3Og01_-bUfXduOXuGfyi)

Released on: 2020-05-13

SHA256: dafa14ac066e6c49ef4545251dbbcbf2b2f39d46523779e923308d2702e4a1b0

Release notes: [Main release](https://github.com/wireapp/wire-android/releases/tag/3.48) + [hotfix](https://github.com/wireapp/wire-android/releases/tag/3.48.915)
