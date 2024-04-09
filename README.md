# Pure Dart UI

![Cover - Pure Dart UI](https://raw.githubusercontent.com/signmotion/pure_dart_ui/master/images/cover.webp)

[![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Pub Package](https://img.shields.io/pub/v/pure_dart_ui.svg?logo=dart&logoColor=00b9fc&color=blue)](https://pub.dartlang.org/packages/pure_dart_ui)
[![Code Size](https://img.shields.io/github/languages/code-size/signmotion/pure_dart_ui?logo=github&logoColor=white)](https://github.com/signmotion/pure_dart_ui)
[![Publisher](https://img.shields.io/pub/publisher/pure_dart_ui)](https://pub.dev/publishers/syrokomskyi.com)

![SDK version](https://badgen.net/pub/sdk-version/pure_dart_ui)
![Supported platforms](https://badgen.net/pub/flutter-platform/pure_dart_ui)
![Supported SDKs](https://badgen.net/pub/dart-platform/pure_dart_ui)

[![Build Status](https://img.shields.io/github/actions/workflow/status/signmotion/pure_dart_ui/dart-ci.yml?logo=github-actions&logoColor=white)](https://github.com/signmotion/pure_dart_ui/actions)
[![Pull Requests](https://img.shields.io/github/issues-pr/signmotion/pure_dart_ui?logo=github&logoColor=white)](https://github.com/signmotion/pure_dart_ui/pulls)
[![Issues](https://img.shields.io/github/issues/signmotion/pure_dart_ui?logo=github&logoColor=white)](https://github.com/signmotion/pure_dart_ui/issues)
[![Pub Score](https://img.shields.io/pub/points/pure_dart_ui?logo=dart&logoColor=00b9fc)](https://pub.dev/packages/pure_dart_ui/score)

Classes from `dart:ui` that run on pure Dart.
Eliminates the error _"Dart library 'dart:ui' is not available on this platform"_.
Feel free to use it in your awesome project or to quickly run a 3rd-party package with Flutter dependencies on the server side or CLI.

[![CodeFactor](https://codefactor.io/repository/github/signmotion/pure_dart_ui/badge)](https://codefactor.io/repository/github/signmotion/pure_dart_ui)

Share some ❤️ and star repo to support the project.

_If you write an article about **PureDartUi** or any of [these](https://pub.dev/packages?q=publisher%3Asyrokomskyi.com&sort=updated) packages, let me know and I'll post the URL of the article in the **README** 🤝_

## Motivation

Sometimes we want to use nice packages from pub.dev on the CLI or server side.
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

## 🚀Usage

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

In other words, you can create your own application or use a 3rd-party package with [dart:ui features](https://api.flutter.dev/flutter/dart-ui/dart-ui-library.html) based on a pure Dart, without depending on the Flutter SDK.

### Use `Color`

```dart
const color = Color(0xffa1b2c3);
```

## Similar Projects

- [universal_io](https://pub.dev/packages/universal_io)
  A cross-platform `dart:io`.
- [universal_html](https://pub.dev/packages/universal_html)
  A cross-platform `dart:html`.

## 👁️What's New

Look at [changelog](https://pub.dev/packages/pure_dart_ui/changelog).

## 🙋‍♀️🙋‍♂️Welcome

Requests and suggestions are warmly welcome.

Contributions are what make the open-source community such a great place to learn, create, take a new skills, and be inspired.

If this is your first contribution, I'll leave you with some of the best links I've found: they will help you get started or/and become even more efficient.

- [Guide to Making a First Contribution](https://github.com/firstcontributions/first-contributions). You will find the guide in your native language.
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute). Longread for deep diving for first-timers and for veterans.
- [Summer Guide from Google](https://youtu.be/qGTQ7dEZXZc).
- [CodeTriangle](https://codetriage.com) Free community tools for contributing to Open Source projects.

The package **PureDartUi** is open-source, stable and well-tested. Development happens on
[GitHub](https://github.com/signmotion/pure_dart_ui). Feel free to report issues
or create a pull-request there.

General questions are best asked on
[StackOverflow](https://stackoverflow.com/questions/tagged/pure_dart_ui).

And here is a curated list of how you can help:

- Documenting the undocumented. Whenever you come across a class, property, or method within our codebase that you're familiar with and notice it lacks documentation, kindly spare a couple of minutes to jot down some helpful notes for your fellow developers.
- Refining the code. While I'm aware it's primarily my responsibility to refactor the code, I wholeheartedly welcome any contributions you're willing to make in this area. Your insights and improvements are appreciated!
- Constructive code reviews. Should you discover a more efficient approach to achieve something, I'm all ears. Your suggestions for enhancement are invaluable.
- Sharing your examples. If you've experimented with our use cases or have crafted some examples of your own, feel free to add them to the `example` directory. Your practical insights can enrich our resource pool.
- Fix typos/grammar mistakes.
- Report bugs and scenarios that are difficult to implement.
- Implement new features by making a pull-request.

Created [with ❤️](https://syrokomskyi.com)
