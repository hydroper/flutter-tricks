# Unused

## Widgets

- [InheritedWidget](https://api.flutter.dev/flutter/widgets/InheritedWidget-class.html)
  - Used for application-widely shared data. Use of observables as below might be useful.

## Observability and Async. Streams

- [Stream](https://api.dart.dev/stable/3.0.5/dart-async/Stream-class.html)
- [ObservableList](https://pub.dev/documentation/observable/latest/observable/ObservableList-class.html) from `observable`:

```dart
var obs = ObservableList.from([initialValue]);
obs.changes.listen(([value = 0]) { // ignore the `= 0`
  // changed
});

// peek/mutation
obs[0];
obs[0] = someValue;
```
