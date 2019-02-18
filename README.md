## Flutter Training

> Mobile users expect their apps to have beautiful designs, smooth animation, and great performance. To deliver on this, developers need to create new features faster than ever without compromising on quality or performance. That's why we build Flutter. 
---- Introducing Flutter, Google's mobile UI framework ----
https://www.youtube.com/watch?v=fq4N0hgOWzU
>
> Flutter Home: https://flutter.io/
>
> Article: https://medium.com/@nhancv/why-i-move-to-flutter-34c4005b96ef

### Overview

- Install
- Setup IDE
- New project
- Convention
- Change Images and App icon
- Change Fonts
- Work with I18n
- Understand App Navigation
- Understand StateLess & StateFull
- Understand Lifecycle
- Work with BLoC and State management
- Understand App Version and Env
- Understand App Module
- Cookbook
- Release
- Testing

### Steps
Father docs: https://flutter.io/docs


#### Install 
https://flutter.io/docs/get-started/install

#### Setup IDE
https://flutter.io/docs/get-started/editor

#### New project
https://flutter.io/docs/get-started/codelab

#### Convention
https://github.com/flutter/flutter/wiki/Style-guide-for-Flutter-repo

#### Change Images and App icon
https://flutter.io/docs/development/ui/assets-and-images

#### Change Fonts
https://flutter.io/docs/development/accessibility-and-localization/accessibility

#### Work with I18n
https://flutter.io/docs/development/accessibility-and-localization/internationalization

#### Understand App Navigation
https://flutter.io/docs/development/ui/navigation

#### Understand StateLess & StateFull
https://flutter.io/docs/development/ui/interactive

#### Understand Lifecycle
- Technical Overview
https://flutter.io/docs/resources/technical-overview
- Inside Flutter
https://flutter.io/docs/resources/inside-flutter
- Stateful Widget Lifecycle
https://flutterbyexample.com/stateful-widget-lifecycle/
```
createState
mounted is true
initState
didChangeDependencies
build
didUpdateWidget
setState
deactivate
dispose
mounted is false
```
- App LifeCycle and Handling Orientation
https://www.youtube.com/watch?v=f9m_Wc4K5v0

#### Work with BLoC and State management
- State management
https://flutter.io/docs/development/data-and-backend/state-mgmt
- JSON
https://flutter.io/docs/development/data-and-backend/json
- Flutter Architecture Samples
http://fluttersamples.com/

#### Understand App Version and Env
- VERSIONING
https://medium.com/@ralphbergmann/versioning-with-flutter-299869e68af4

Add version line to pubspec.yaml
```
name: hello
description: A new Flutter project.
version: 1.0.0+1         # add this
dependencies:
  flutter:
    sdk: flutter
...
```
Then run
```
flutter build apk --build-name=1.0.3
flutter build apk --build-number=3
flutter build apk --build-name=1.0.3 --build-number=3
```

- ENVIRONMENT
```
flutter run -t lib/Main/main_staging.dart

# Update FLUTTER_TARGET at ios/Flutter/Generated.xcconfig 
FLUTTER_TARGET=lib/Main/main_staging.dart
```

#### Understand App Module
- Using packages
https://flutter.io/docs/development/packages-and-plugins/using-packages
- Writing custom platform-specific code
https://flutter.io/docs/development/platform-integration/platform-channels

#### Cookbook
https://flutter.io/docs/cookbook

#### Release 
- Android
https://flutter.io/docs/deployment/android
- iOS
https://flutter.io/docs/deployment/ios

#### Testing
https://flutter.io/docs/testing










