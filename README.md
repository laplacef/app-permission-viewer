# app-permission-viewer

An Android app that lists every installed application and the permissions it requests.

Built with Kotlin and Jetpack Compose. It reads the installed packages through Android's `PackageManager`, gathers each app's requested permissions, and shows them grouped by app in a scrollable list. Apps with no requested permissions are omitted, and both the app list and each permission set are sorted alphabetically.

## Build

Open the project in Android Studio, or build from the command line:

```bash
./gradlew assembleDebug
```

The debug APK is written to `app/build/outputs/apk/debug/`.
