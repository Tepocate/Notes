# notes

This is my first flutter app called notes. Basically followed an online tutorial on how to create this simple app to help me learn how easy it is to work in Flutter. The app will allow you to create a note give it a title and type a body. You will also be able to change the color of the note you created. The link can be found [here](https://medium.com/aubergine-solutions/creating-a-note-taking-app-in-flutter-dart-f50852993cd0).

## Prerequisites

All you really need is android studio to install latest Android SDK, Platform-Tools, and Build-Tools

## Getting Started

All files to install the app are included. You can easily build this to you android phone with the following steps:

- Plug your android device to your PC (Note: Make sure you have Developer options and USB debugging option enabled on your device)
- Make sure you have the latest Android SDK, Platform-Tools, and Build-Tools
- run the `flutter devices` command to verify Flutter can see you Android device
- Make sure you are in the location where the android folder is located for the app `cd notes`
- If you only have one device connected and `flutter devices` only shows one device you can just use the command `flutter run` to install the app. Otherwise you need to specify the device you want it installed on. For instance if you run `flutter devices command` and see `SM G950U1 • 9887fc41594630315a • android-arm • Android 7.0 (API 24)` as the output you would run `flutter run -d 9887fc41594630315a` to install the app on that device.
