# cupertino_localizations

Provider localization for cupertino. just en,ar and zh 
if you don't wont to use the default.
You can use it to fixed the error: The getter 'pasteButtonLabel' was called on null.

## Usage
```dart
MaterialApp(
  locale: Locale('ar', ''),
  localizationsDelegates: [
    GlobalCupertinoLocalizations.delegate,
    GlobalMaterialLocalizations.delegate,
    GlobalWidgetsLocalizations.delegate,
  ],
  supportedLocales: [
    const Locale('zh', 'CH'),
    const Locale('ar', ''),
    const Locale('en', 'US'),
  ],
 ...
}
```
## Contributing
Feel free to send me a pull request to add your langage.

## Acknowledgment
This library base on the work of [crazy365966834](https://github.com/crazy365966834/flutter_cupertino_localizations/) thank you.