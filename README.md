# Jeep Box Hero

Jeep Box Hero is a landscape-oriented record shop simulation with a story inspired by Filipino music and OPM. Step into Jeep Box Records, learn the ropes from Tito Ramon, help customers find the records they are looking for, and manage the shop's shelves and sales. Explore the shop, inspect albums, and complete customer encounters through dialogue and music.

## Requirements

- Flutter SDK (Dart 3 or later)
- For Android: Android Studio or Android SDK, plus an emulator or USB-connected device
- For Windows desktop: Visual Studio with the Desktop development with C++ workload

## Run the game

From the project directory, install the Flutter packages:

```powershell
flutter pub get
```

Check which targets are available:

```powershell
flutter devices
```

Run on a connected Android device or emulator:

```powershell
flutter run
```

Or select a target explicitly:

```powershell
flutter run -d windows
flutter run -d chrome
```

## Build and install

### Android

Build a release APK:

```powershell
flutter build apk --release
```

The APK is created at `build\app\outputs\flutter-apk\app-release.apk`. With a device connected and USB debugging enabled, install it using:

```powershell
flutter install
```

Alternatively, install the APK directly with Android Debug Bridge:

```powershell
adb install build\app\outputs\flutter-apk\app-release.apk
```

### Windows

Build the release desktop app:

```powershell
flutter build windows --release
```

The app is generated under `build\windows\x64\runner\Release`. Run `jeepboxhero.exe` from that folder; distribute the entire folder so the app's required files are included.
