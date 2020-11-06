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


## Wire Android 3.58.957

Download: [link](https://drive.google.com/file/d/1JkC80d_UHWcLYcYonyhK3Gzar_lCMeRN/view?usp=sharing)

Released on: 2020-10-30

SHA256: `5be9786b70a8122c00b71af01da04d2661a0a6668b64732e64059f75de26f65d`

Release notes:
* [Main release](https://github.com/wireapp/wire-android/releases/tag/3.58)
On top of that, this release uses [wire-signals](https://github.com/wireapp/wire-signals) v0.2.4, the first version after a major refactoring.

## Wire Android 3.57.944

Download: [link](https://drive.google.com/file/d/1eVBepz0E5VNLCM6rLBjiOV8U0EXODdiK)

Released on: 2020-10-05

SHA256: `3ef0be78d59b3995c6d61f589abcb9dcde4ba086bf4cfe0c0802cad303f0c01c`

Release notes:
* [3.56](https://github.com/wireapp/wire-android/releases/tag/3.56)
* [3.57](https://github.com/wireapp/wire-android/releases/tag/3.57)
The most important change: New conference calls - better quality and more people than before can participate in an e2ee call.


## Wire Android 3.55.939

Download: [link](https://drive.google.com/file/d/1e9e1xDLJ_8na0ATpjjnDsShZnq4Gas7z)

Released on: 2020-09-15

SHA256: `78389ab42cd240253007a67ed90fe9010ccafa925a235b302bc63a0396fda31d`

Release notes:
* [3.53](https://github.com/wireapp/wire-android/releases/tag/3.53)
* [3.54](https://github.com/wireapp/wire-android/releases/tag/3.54)
* [3.55](https://github.com/wireapp/wire-android/releases/tag/3.55)
I skipped two releases due to vacations and other work. The most important changes are dropped support for Android 5 & 6, and the new backups functionality.

## Wire Android 3.52.927


Download: [link](https://drive.google.com/file/d/1pIM7RYh6OT0QxCVtvOXlR2ZYVGogrz3X)

Released on: 2020-07-21

SHA256: `17ca5459e39f22f6dcadc7e2c352e602de1fbf70461b71b23d9baffcf423b0ce`

Release notes: [Main release](https://github.com/wireapp/wire-android/releases/tag/3.52)

## Wire Android 3.51.926


Download: [link](https://drive.google.com/file/d/1w_JcKaFLnY4XOwtJOvJp9FM7Z30UtdMv)

Released on: 2020-07-08

SHA256: `c7a660ec53f8281716d4eb870384d17640794435a2e5f3de24c001f9a405c752`

Release notes: [Main release](https://github.com/wireapp/wire-android/releases/tag/3.51)

This is the first release that uses [wire-signals](https://github.com/wireapp/wire-signals)

## Wire Android 3.50.922


Download: [link](https://drive.google.com/file/d/1GRcpTMVjYYEuFj3fOvvJj6X1GhQ0hbGJ)

Released on: 2020-06-11

SHA256: `f90419a7f530083a85f2dfc6438f5d0f101914ace53037038cecf48a65826d26`

Release notes: [Main release](https://github.com/wireapp/wire-android/releases/tag/3.50)

## Wire Android 3.49.918


Download: [link](https://drive.google.com/file/d/116XWP4ZY7gJu9RsQMlX1cjnMdkvHCV2U)

Released on: 2020-05-28

SHA256: `9c95014c5b08ff8b33625a4604416c83864a4a8644aefa972498bab67d4583a9`

Release notes: [Main release](https://github.com/wireapp/wire-android/releases/tag/3.49) + [hotfix](https://github.com/wireapp/wire-android/releases/tag/3.49.918)

## Wire Android 3.48.915


Download: [link](https://drive.google.com/open?id=1qJaWusjulqVq3Og01_-bUfXduOXuGfyi)

Released on: 2020-05-13

SHA256: `dafa14ac066e6c49ef4545251dbbcbf2b2f39d46523779e923308d2702e4a1b0`

Release notes: [Main release](https://github.com/wireapp/wire-android/releases/tag/3.48) + [hotfix](https://github.com/wireapp/wire-android/releases/tag/3.48.915)
