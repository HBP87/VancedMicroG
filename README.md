# This is a fork repo.
Forked from @inotia00 's [VancedMicroG](https://github.com/inotia00/VancedMicroG)
# Vanced MicroG

![Build Status](https://github.com/TeamVanced/VancedMicroG/workflows/Debug%20APK%20Builder/badge.svg)
[![Github All Releases](https://img.shields.io/github/downloads/HBP87/VancedMicroG/total.svg)](https://github.com/HBP87/VancedMicroG/releases) [![Github All Releases](https://img.shields.io/github/release/HBP87/VancedMicroG.svg)](https://github.com/HBP87/VancedMicroG/releases)

microG GmsCore is a FLOSS (Free/Libre Open Source Software) framework to allow applications designed for Google Play Services to run on systems, where Play Services is not available.

This fork tweaks MicroG to be usable by applications that require Google authentication such as Vanced and ReVanced Youtube.

## Notable changes

- No longer a system app
- Package name changed from `com.google.android.gms` to `com.mgoogle.android.gms` to support installation alongside the official MicroG
- Removed unnecessary features:
  - Ads
  - Analytics
  - Car
  - Droidguard
  - Exposure-Notifications
  - Feedback
  - Firebase
  - Games
  - Maps
  - Recovery
  - Registering app permissions
  - SafetyNet
  - Self-Check
  - Search
  - TapAndPay
  - Wallet
  - Wear-Api
- Removed all permissions, as none are required for Google authentication

## Credits

- Source Code for MicroG 0.2.25.224113 was provided by [@OxrxL](https://github.com/OxrxL)
- [@shadow578](https://github.com/shadow578)'s commit used to apply ReVanced's `SPOOFED_PACKAGE_SIGNATURE`