# botlist.space Translations
The locale files used to translate the site into different languages.

## How to translate
1. Navigate into the `locales` folder.
2. Copy all data from `en-us.json` into a new file called `lang.json` but replace `lang` with the shortened version of the translated language.
3. Translate everything inside that file.
4. For every other locale file, add a property called `language_name` but replace `name` with the English version of that language. For the translated value, put the language but in the language of that locale file. For example in `en-us.json`, it would be `"language_english": "English"`.
5. Update the `Translators` table within the README.md file to include your GitHub username and language.
6. Submit a Pull Request and we'll review it soon.

## Translators

Language             | Name
-------------------- | ------------------
Dutch                | @GeoffreyWesthoff
Chinese (Simplified) | @austinhuang0131
