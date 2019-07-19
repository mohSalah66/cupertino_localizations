# Cupertino Localizations
This package is to reslove the issue with 
```The getter 'pasteButtonLabel' was called on null.``` on IOS when selecting a text.

## Usage
```
MaterialApp(
  locale: Locale('ar', ''),
  localizationsDelegates: [
    GlobalCupertinoLocalizations.delegate,
    GlobalMaterialLocalizations.delegate,
    GlobalWidgetsLocalizations.delegate,
  ],
  supportedLocales: [
    const Locale('ar', ''),
    const Locale('en', 'US'),
  ],
 ...
}
```


## Contributing
Feel free to send me a pull request to add you Langage

## Acknowledgment
This library base on the work of [Thank you crazy365966834](https://github.com/crazy365966834 flutter_cupertino_localizations/)
