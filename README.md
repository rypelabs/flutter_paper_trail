# flutter_paper_trail

A new flutter plugin project.

## Getting Started

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).

For help on editing plugin code, view the [documentation](https://flutter.io/platform-plugins/#edit-code).


# flutter_paper_trail

Send logs to Papertrail


# Usage


Example:

```dart
import 'package:flutter_paper_trail/flutter_paper_trail.dart';

FlutterPaperTrail.initLogger(
        hostName: "secret.papertrailapp.com",
        programName: "flutter-test-app",
        port: 9999,
        machineName: "Simulator(iPhone8)");
    //for machine name use Flutter DeviceInfoPlugin

FlutterPaperTrail.logError("My message");
```

