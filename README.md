# infohub
[![mac](https://img.shields.io/badge/Mac-Flutter-00bfff.svg)]()

## Startup Flutter Project
### 1. Get the Flutter SDK
Download the SDK via https://flutter.io/docs/get-started/install/macos

### 2. Set Flutter path
By typing 
```shell
source add-flutter-path.sh
```
Verify the setting by 
```shell
flutter doctor
```

#### Ex. check result
```shell
[✓] Flutter (Channel stable, v1.0.0, on Mac OS X 10.13.6 17G2307, locale en-TH)
[✓] Android toolchain - develop for Android devices (Android SDK 28.0.3)
[!] iOS toolchain - develop for iOS devices (Xcode 10.1)
    ✗ Verify that all connected devices have been paired with this computer in Xcode.
      If all devices have been paired, libimobiledevice and ideviceinstaller may require updating.
      To update with Brew, run:
        brew update
        brew uninstall --ignore-dependencies libimobiledevice
        brew uninstall --ignore-dependencies usbmuxd
        brew install --HEAD usbmuxd
        brew unlink usbmuxd
        brew link usbmuxd
        brew install --HEAD libimobiledevice
        brew install ideviceinstaller
[✓] Android Studio (version 3.2)
[!] VS Code (version 1.30.1)
[✓] Connected device (2 available)
```

### 3. Setup IDE
#### 3.1 iOS (XCode) and simulator
Follow by this step https://flutter.io/docs/get-started/install/macos#install-xcode

#### 3.2 Android
Follow by this step https://flutter.io/docs/get-started/install/macos#android-setup. 
Install plugin to Android Studio, at `Android Studio -> Preference -> Plugins`, search keyword `dart` and `flutter` in search box to install it. And then click on "Search in repositories" in `No plugins found. Search in repositories`

##### Note: For Android, don't forget install `NDK` in `SDK Tools` tab


