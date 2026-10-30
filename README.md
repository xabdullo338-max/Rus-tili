# RUSSIAN PRO — Android starter

A minimal native Android/Kotlin starter for Uzbek-speaking learners at basic Russian level.

## Included in this first prototype
- Native Android chat screen
- Russian speech recognition via the device speech service (`ru-RU`)
- Russian text-to-speech replies
- Basic offline demo dialogue rules

## Important limitations
- This is a starter source project, not a compiled APK.
- The current tutor replies are scripted demo responses, not generative AI.
- Speech recognition availability and offline support depend on the Android device and installed speech services.
- For real open-ended AI conversation, connect a backend that protects the AI API key. Do not put secret API keys inside the Android app.

## Build
1. Open this folder in Android Studio (Hedgehog or newer recommended).
2. Allow Gradle sync and install Android SDK 35 if prompted.
3. Run on an Android phone or emulator.
4. Grant microphone permission and test the microphone button.

Package: `com.russianpro.app`
