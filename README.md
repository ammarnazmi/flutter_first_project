# flutter-first-project

My first Flutter app, for learning Flutter. It runs on Android, iOS, web, macOS, Windows and Linux.

## Requirements

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (Dart 3.13 or newer)
- An emulator or simulator (Android Studio or Xcode), or a real device

Check your setup:

```bash
flutter doctor
```

## Getting started

```bash
flutter pub get                     # install packages
flutter emulators                   # list emulators
flutter emulators --launch Pixel_6  # start one
flutter run                         # run the app
```

While the app is running, press `r` for hot reload and `q` to quit.

## Project structure

| Path | What it is |
|---|---|
| `lib/` | App code (start at `lib/main.dart`) |
| `test/` | Tests (`flutter test`) |
| `pubspec.yaml` | Project settings and packages |
| `android/`, `ios/`, `web/`, `macos/`, `windows/`, `linux/` | Platform-specific files |

## Useful commands

```bash
flutter test           # run tests
flutter analyze        # check code for problems
flutter build apk      # build an Android release
```
