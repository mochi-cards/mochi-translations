# Translate Mochi

Community-powered translations for [Mochi](https://mochi.cards/).

## Contributing
1. Fork this repo
2. Open `translations.edn` in your favorite text editor.
3. Add a new language, or add translations to an existing language.

## File format
The `translations.edn` file is a large map of IETF language tags to localization maps.
```clj
{:en
 {:side-bar/settings "Settings"
  ... }
 :ja
 {:side-bar/settings "設定"
  ... }}
```
To add a new language, simply add a new key that matches the IETF tag for your language. Then copy the key-value pairs from the :en dictionary and change the strings to your language.

## Testing your changes
1. Open Mochi
2. Navigate to Settings → General
3. Under "Custom translations", upload your translation file.
4. In the same window, under "Language", choose the language you're contributing to.
