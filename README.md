# flutter-docs
My own notes &amp; documentation for flutter

[Running Flutter Apps](#running-flutter-apps)
- [Run the main dart file](#run-the-main-dart-file)
- [Run an alternate dart file](#run-an-alternate-dart-file)
- [Run targeting a device](#run-targeting-a-device)
- [See available devices](#see-available-devices)<br>

[Syntax](#syntax)
- [Public vs private](#public-vs-private)

[Elements](#elements)
- [Buttons](#buttons)

## Running Flutter Apps

### Run the main dart file
`
flutter run
`

### Run an alternate dart file
`
flutter run -t lib/otherFile.dart
`

### Run, targeting a device
`
flutter -v -d macos run
`

### See available devices
`flutter devices`

## Syntax

### Public vs Private
Public:
```dart
class MyClass
```

Private:
```dart
class _MyClass
```


## Elements

### Buttons

#### ElevatedButton 
This automatically picks up the main theme of the app - so it will be in line with your color scheme automatically.
```
ElevatedButton(onPressed: onPressedHandler, child: child)
```

#### FloatingActionButton
Places a circular button that picks up the main theme.
```
FloatinActionButton(onPressed: hanlder, foregroundColor: Colors.color, child: child)
```
