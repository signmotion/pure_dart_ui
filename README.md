# Pure Dart UI

![Cover - Pure Dart UI](https://raw.githubusercontent.com/signmotion/pure_dart_ui/master/images/cover.webp)

[![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Pub Package](https://img.shields.io/pub/v/pure_dart_ui.svg?logo=dart&logoColor=00b9fc&color=blue)](https://pub.dartlang.org/packages/pure_dart_ui)
[![Code Size](https://img.shields.io/github/languages/code-size/signmotion/pure_dart_ui?logo=github&logoColor=white)](https://github.com/signmotion/pure_dart_ui)
[![Publisher](https://img.shields.io/pub/publisher/pure_dart_ui)](https://pub.dev/publishers/syrokomskyi.com)

[![Build Status](https://img.shields.io/github/actions/workflow/status/signmotion/pure_dart_ui/dart-ci.yml?logo=github-actions&logoColor=white)](https://github.com/signmotion/pure_dart_ui/actions)
[![Pull Requests](https://img.shields.io/github/issues-pr/signmotion/pure_dart_ui?logo=github&logoColor=white)](https://github.com/signmotion/pure_dart_ui/pulls)
[![Issues](https://img.shields.io/github/issues/signmotion/pure_dart_ui?logo=github&logoColor=white)](https://github.com/signmotion/pure_dart_ui/issues)
[![Pub Score](https://img.shields.io/pub/points/pure_dart_ui?logo=dart&logoColor=00b9fc)](https://pub.dev/packages/pure_dart_ui/score)

Classes from `dart.ui` that run on pure Dart.
Eliminates the error _"Dart library 'dart:ui' is not available on this platform"_.
Feel free to use it in your awesome project.

| Android | iOS | Linux | MacOS | Web | Windows |              |
| :-----: | :-: | :---: | :---: | :-: | :-----: | :----------- |
|   ✅    | ✅  |  ✅   |  ✅   | ✅  |   ✅    | **platform** |

| Dart | Flutter |         |
| :--: | :-----: | :------ |
|  ✅  |   ✅    | **SDK** |

Share some ❤️ and star repo to support the project.

## Motivation

Sometimes we want to use nice packages from pub.dev on the server side or CLI.
But (sometimes) the needed package has dependencies on Flutter...

I created `pure_dart_ui` to address this injustice in a single line (see `Usage` section below).

## Features

### Classes independed of the Flutter SDK

- `Color`
- `Offset`
- `Rect`
- `Size`

### Functions independed of the Flutter SDK

- `clampDouble`
- `lerpDouble`

## Usage

Add the package `pure_dart_ui` to `pubspec.yaml` and import the library:

```dart
import 'package:pure_dart_ui/pure_dart_ui.dart';
```

Or, if you want to fix the error stream when you run `dart main.dart`, then replace the line

```dart
// replace this import and be happy
import 'dart:ui';
```

with the line above in the desired 3rd-party package.

Use the classes and functions in this package same way you used `Flutter dart:ui`.

You can create your own application or use a 3rd-party package with [dart:ui](https://api.flutter.dev/flutter/dart-ui/dart-ui-library.html) based on a pure Dart, without depending on the Flutter SDK.

### Use `Color`

```dart
const color = Color(0xFFAABBCC);
```

## Welcome to Inspiration

Requests and suggestions are warmly welcome.

Contributions are what make the open-source community such a great place to learn, create, and be inspired.

If this is your first contribution, I'll leave you with some of the best links I've found: they will help you get started or/and become even more efficient.

- [Guide to Making a First Contribution](https://github.com/firstcontributions/first-contributions). You will find the guide in your native language.
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute). Longread for deep diving for first-timers and for veterans.
- [Summer Guide from Google](https://youtu.be/qGTQ7dEZXZc).

The package **PureDartUi** is open-source, stable and well-tested. Development happens on
[GitHub](https://github.com/signmotion/pure_dart_ui). Feel free to report issues
or create a pull-request there.

General questions are best asked on
[StackOverflow](https://stackoverflow.com/questions/tagged/pure_dart_ui).

And here is a curated list of how you can help:

- Report parts of the documentation that are unclear.
- Fix typos/grammar mistakes.
- Update the documentation or add examples.
- Report bugs and scenarios that are difficult to implement.
- Implement new features by making a pull-request (look below).

Created [with ❤️](https://syrokomskyi.com)
