# flutter-docs
My own notes &amp; documentation for flutter

## Running Flutter Apps

### Runing the main.dart file
`
flutter run
`

### Run an alternate dart file
`
flutter run -t lib/otherFile.dart
`

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
