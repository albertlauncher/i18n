# Albert launcher translations



<!--  THIS SECTION AND TRANSLATIONS IN GENERAL NEED AN OVERHAUL
# Adding translations
## How to add a translation file
* Get Qt Linguist.
* Fork and git clone --recursive` the Albert repository.
* Open a terminal and `cd` into the `i18n` folder (of the (sub)project you want to translate).
* Create a Qt translation file for your desired language, e.g. by converting an existing one: E.g. for spanish: `lconvert -drop-translations i18n/albert_de.ts -target-language es -o i18n/albert_es.ts`
* Populate the translation file(s) using the meta tool. `./metatool.py lupdate`
* Optionally pass the file to GPT, which does a decent job at translating ts files.
* Open the file using Qt Linguist and review/translate.
* Save, commit, push and send a PR.

The core app and plugins maintain _separate sets of translations_.
Translations are stored in the `i18n` subdirectory of each project. 


* Open a terminal and `cd` into the `i18n` folder of the (sub)project you want to translate.
* Create a Qt translation file for your desired language, e.g. by converting an existing one: E.g. for spanish:
  ```sh
  lconvert -drop-translations albert_de.ts -target-language es -o albert_es.ts
  ```
* Add translations. `QtLinguist` is the recommended editor for `*.ts` files.
* Eventually save, commit, push and send a PR.

# Python plugin translations

[TODO]
-->
