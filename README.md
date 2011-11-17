I18n, G11n, L10n for [Charm](http://charmhq.com/)—you name it.

This is in beta—not everything is translated yet, but it's getting there!



### Submitting translations

Please fork and submit pull requests to submit new languages or fixes.
To be included in Charm, please also update `languages.txt` in the root folder of
this project to include the name of the language as it should appear in a language
selector dropdown. We'd love to have maintainers for specific languages, so please
volunteer! :)

To create a new localization, add a folder with the corresponding 
[ISO 639-1 code](http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes).

Each folder contains two files, here is for example the canonical english translation:

* `en.coffee` contains strings for Underscore.js templates
* `en.yml` contains strings for Rails ERB templates

All files must be encoded in UTF-8.

When new features are added to Charm or changes in translations are required,
please refer to any updates to the files in `en`.



### Region-specific locales

You can also submit region-specific locales, like `de-AT` (Austrian German). 
If a translation is not found in the region-specific file, it falls back to the
language (`de` in this case), and if it is not found there either it falls back
to `en`.



### License/Permission to use

This work is licensed under a
[Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License](http://creativecommons.org/licenses/by-nc-nd/3.0/).

By submitting translations you agree to grant Slash7 LLC an additional perpetual, non-exclusive,
irrevocable license to deal with the data without restriction, including without limitation 
the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the translations.