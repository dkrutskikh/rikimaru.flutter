# Flutter Architecture Component

[![pub package](https://img.shields.io/badge/pub-0.0.1-orange.svg)](https://pub.dartlang.org/packages/architecture_component)
[![pub package](https://img.shields.io/badge/donate-Paypal-brightgreen.svg)](https://www.paypal.me/tranductam)

The new Flutter Package which supported Mobile Architecture Component in Flutter.

## Getting Started

For help getting started with Flutter, view the [online documentation](https://flutter.io/).

For help getting started with Flutter Architecture Component, view the [full documentation](https://github.com/MrNinja/rikimaru.flutter/blob/master/README.md)

## Prepare dependencies
To use this package, add `architecture_component` and `architecture_generator` as a [dev_dependencies in your pubspec.yaml file](https://flutter.io/platform-plugins/).
```
...
dependencies:
  flutter:
    sdk: flutter

  cupertino_icons: ^0.1.2
  architecture_component: '>=0.0.1 <1.0.0'  # => Flutter Architecture Component package.

dev_dependencies:
  flutter_test:
    sdk: flutter

  architecture_generator: '>=0.0.1 <1.0.0'  # => Architecture Source Generator package.
  build_runner: ^1.0.0
  test: ^1.0.0

flutter:
  uses-material-design: true
...
```

## Flutter Architecture Component 

* TODO: To be defined.

### [ViewModel] - The utility class provide the instance of model data each screen.

* TODO: To be defined.

### [LiveData] - The observable data holder class.

* TODO: To be defined.

### [ScreenWidget] - Base widget define the screen in project.

* TODO: To be defined.

### [Repository] - Working class provide the ways to contact to storage module.

* TODO: To be defined.

### [DiskIOWorker] - Local storage worker class (Local databases, caches, preferences, etc).

* TODO: To be defined.

### [NetworkWorker] - Remote server connection controller.

* TODO: To be defined.
