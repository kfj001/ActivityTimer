# Activity Timer

This is a simple Apache Cordova scaffold wrapping your a single-page web app that embodies a timer for some abstract activity.

## Dev Container Users
This project has a configured devcontainer environment which you can use to build the project for Android devices.

## Contents
- `www/index.html` — single-page web app.
- `config.xml` — basic Cordova app configuration.
- `package.json` — convenience scripts for common Cordova commands.
- `res/` — placeholder directory for icons/splashes.

## Prerequisites
- Node.js and npm installed (https://nodejs.org/)
- Cordova CLI: `npm install -g cordova`

Android (Windows) specific:
- Java JDK (17 reccomended, 21 latest)
- Android SDK (via Android Studio or Command line tools)
- Set `ANDROID_HOME` and add platform tools to PATH

iOS (macOS only):
- Xcode (required for building/running on iOS devices/simulators)

## Quick commands (PowerShell)

### Add platforms
cordova platform add android
### On macOS only:
cordova platform add ios

## Build
cordova build android
cordova build ios

## Run on emulator/device
cordova run android --emulator
cordova run android --device

### Notes
- iOS builds require macOS with Xcode installed. You cannot build iOS targets on Windows.
- If you already have an existing Cordova project, you can copy `www/index.html` into its `www/` folder and merge `config.xml` settings.