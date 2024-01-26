# Pure Dart UI

![Cover - Pure Dart UI](https://raw.githubusercontent.com/signmotion/pure_dart_ui/master/images/cover.webp)

The classes from `dart.ui` that run on pure Dart.

Eliminates the error _"Dart library 'dart:ui' is not available on this platform"_.

## Features

### Classes independed of the Flutter SDK

- Color
- Offset
- Rect
- Size

### Functions independed of the Flutter SDK

- clampDouble
- lerpDouble()

## Usage

Add this package to `pubspec.yaml` and import the library:

```dart
import 'package:pure_dart_ui/pure_dart_ui.dart';
```

Use the classes and functions in this package same way you used `Flutter dart:ui`.

You can create your own application with [dart:ui](https://api.flutter.dev/flutter/dart-ui/dart-ui-library.html) based on a pure Dart, without depending on the Flutter SDK.

## License

[MIT](LICENSE)
