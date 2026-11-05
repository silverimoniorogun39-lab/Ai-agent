# Hey Agent — Native Android Project

## Build Instructions
1. Open this directory in Android Studio.
2. Select 'app' module.
3. Connect your Samsung Galaxy S22 Ultra (SM-S908U) via USB with USB debugging enabled.
4. Click Run (Shift + F10) or execute in terminal:
   `./gradlew assembleDebug`
5. Install on device:
   `adb install -r app/build/outputs/apk/debug/app-debug.apk`
