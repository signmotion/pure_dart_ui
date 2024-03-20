# Pure Dart UI

![Cover - Pure Dart UI](https://raw.githubusercontent.com/signmotion/pure_dart_ui/master/images/cover.webp)

[![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Pub Package](https://img.shields.io/badge/doc-pure_dart_ui-blue)](https://pub.dartlang.org/packages/pure_dart_ui)
[![Build Status](https://github.com/signmotion/pure_dart_ui/actions/workflows/dart-ci.yml/badge.svg)](https://github.com/signmotion/pure_dart_ui/actions/workflows/dart-ci.yml)
[![Publisher](https://img.shields.io/pub/publisher/pure_dart_ui)](https://pub.dev/publishers/syrokomskyi.com)

The classes from `dart.ui` that run on pure Dart.
Eliminates the error _"Dart library 'dart:ui' is not available on this platform"_.
Feel free to use it in your awesome project.

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

Add this package to `pubspec.yaml` and import the library:

```dart
import 'package:pure_dart_ui/pure_dart_ui.dart';
```

Use the classes and functions in this package same way you used `Flutter dart:ui`.

You can create your own application with [dart:ui](https://api.flutter.dev/flutter/dart-ui/dart-ui-library.html) based on a pure Dart, without depending on the Flutter SDK.

### Use `Color`

```dart
const color = Color(0xFFAABBCC);
```

## Welcome

Requests and suggestions are warmly welcome.

This package is open-source, stable and well-tested. Development happens on
[GitHub](https://github.com/signmotion/pure_dart_ui). Feel free to report issues
or create a pull-request there.

General questions are best asked on
[StackOverflow](https://stackoverflow.com/questions/tagged/pure_dart_ui).
