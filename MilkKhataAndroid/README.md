# Milk Khata — Android App

This project packages the standalone offline-first `milk-khata.html` SPA inside a lightweight Android WebView shell.

## Native-app improvements
- Native splash screen with Milk Khata branding and app icon.
- Branded launcher icon.
- Android back button closes the top-most SPA modal first, then navigates WebView history, then exits.
- Native Android share sheet for customer summaries without a phone number.
- Native Android file picker for exporting the JSON backup.
- Native Android Print framework for PDF export; choose **Save as PDF** in the Android print dialog.
- Photo/file chooser support for delivery entries.
- Fully offline app data remains in WebView `localStorage`.

## Build
Open the `MilkKhataAndroid` folder in Android Studio and let it sync the Gradle project.

Then use:
**Build → Build APK(s)**

Debug APK output:
`app/build/outputs/apk/debug/app-debug.apk`

No server is required at runtime.
