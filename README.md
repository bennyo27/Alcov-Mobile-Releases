# Alcov Android preview downloads

This repository distributes Alcov Android preview APKs and signed update information. The application source repository remains private.

## Install

Download the APK from the latest release and open it on your Android phone. To retain your current app data, install it as an update over the existing Alcov preview; do not uninstall first. Android asks you to allow installation from the browser or file manager and then confirm the update.

An older Alcov build needs this manual installation once to gain **App updates**. After installing an updater-enabled build, open Alcov's menu, choose **App updates**, and check for updates. The app verifies signed metadata, package identity and APK signing identity before handing installation to Android.

The preview is for testing. Each release describes its changes and validation. A matching signing identity is required for an in-place upgrade; Android will reject a mismatched package.

## Release files

- Android APK.
- `update.json`: signed preview update envelope used by the app.
- `SHA256SUMS`: download checksums.
- Applicable third-party runtime sources/notices.

The app's update feed is `https://github.com/bennyo27/Alcov-Mobile-Releases/releases/latest/download/update.json`.
