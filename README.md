# [DEPRECATED] Agora Flutter WebRTC Quickstart 

*其他语言版本： [简体中文](README.zh.md)*

This package `agora_flutter_webrtc` is no longer supported by Agora.io as it is using a deprecated version of Agora's Flutter SDK. To get started with [Agora's Flutter SDK](https://pub.dev/packages/agora_rtc_engine) you can refer the QuickStart guide given over [here](https://github.com/AgoraIO-Community/Agora-Flutter-Quickstart)

This tutorial describes how to create an Agora account and build a sample app with Agora using [Flutter](https://flutter.io/).

## Prerequisites
- Agora.io [Developer Account](https://dashboard.agora.io/signin/)
- [Flutter](https://flutter.io/) 1.0.0

## Quick Start
This repository shows you how to use Agora Flutter SDK to build a simple video call app. It demonstrates you how to:

- Join / leave a channel
- Mute / unmute audio
- Switch camera views
- Layout multiple video views

![Screenshot-1](screen-shoot1.jpeg)
![Screenshot-2](screen-shoot2.jpeg)
![Screenshot-3](screen-shoot3.jpeg)
![Screenshot-4](screen-shoot4.jpeg)


### Create an Account and Obtain an App ID
To build and run the sample application, first obtain an app ID: 

1. Create a developer account at [agora.io](https://dashboard.agora.io/signin/). Once you finish the sign-up process, you are redirected to the dashboard.
2. Navigate in the dashboard tree on the left to **Projects** > **Project List**.
3. Copy the app ID that you obtain from the dashboard into a text file. You will use this when you launch the app.

### Update and Run the Sample Application

Open the [entry.dart](lib/pages/entry.dart) file and add the app ID.

```dart
  final String _appId = "<Your AppId>";
```

Run the `packages get` command in your project directory:

```bash  
  # install dependencies
  flutter packages get
```

Once the build is complete, run the `run` command to start the app.

```bash
  # start app
  flutter run
```

**We recommend you to use IDE to control overall build process during development**

Details about how to set up the IDE please take a look at [here](https://flutter.io/docs/get-started/editor?tab=vscode)

## Resources
* Complete [API documentation](https://docs.agora.io/en/) at the Developer Center
* [File bugs about this sample](https://github.com/AgoraIO-Community/Agora-Flutter-Quickstart/issues)
* [Flutter lab: Write your first Flutter app](https://flutter.io/docs/get-started/codelab)
* [Flutter cookbook: Useful Flutter samples](https://flutter.io/docs/cookbook)
* [Flutter online documentation](https://flutter.io/docs), which offers tutorials, samples, guidance on mobile development, and a full API reference.

## Credit
https://pub.dartlang.org/packages/permission_handler

## License
This software is under the MIT License (MIT).
