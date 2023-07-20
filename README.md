# Flutter Tricks

## Widgets

- [InheritedWidget](https://api.flutter.dev/flutter/widgets/InheritedWidget-class.html)

## Observability and Async. Streams

- [ObservableList](https://pub.dev/documentation/observable/latest/observable/ObservableList-class.html) from `observable`:

```dart
var obs = ObservableList<int>.from([initialValue]);
obs.changes.listen(([value = 0]) {
  // changed
});
```
