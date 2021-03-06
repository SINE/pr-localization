Project Reality: BF2 Community Localization
---------------------

https://github.com/realitymod/pr-localization

This repository is for openly maintaining the [Project Reality: BF2](http://www.realitymod.com) localization files for all the different languages.

For community contributions, please make a make a **fork** and submit a [pull request](https://help.github.com/articles/using-pull-requests).

Editing guide
---------------------

We recommend contributors use [Notepad++](https://notepad-plus-plus.org/) to edit the .utxt files.

<p align="center">
<img src="http://media.realitymod.com/misc/prl18n-notepad-guide.jpg" alt="Example" title="Example" width=700 height=250 />
</p>

It is helpful to have View > Show Symbol > Show White Space and TAB enabled in Notepad++.

Testing translations
---------------------

To test your changes in the current version of PR:BF2, just edit the necessary files located in:

>`<PR Install Dir>/mods/pr/localization/<language>`

Please make sure you have tested your changes and have confirmed they are working correctly **prior to submitting a pull request!**

Change your language in PRLauncher > Options > Global > Language

See below if characters are missing in the font.

What not to translate
---------------------

In `pr.utxt`:
* `HUD_TEAMNAME_ENGLISH_*` should not be translated.
* `HUD_TEXT_MENU_REINFORCEMENTS` should not be translated.
* `HUD_TEXT_MENU_CACHES` should not be translated.
* `HUD_TEXT_MENU_ENEMY_ASSETS` should not be translated.
* `HUD_TEXT_MENU_ASSETS_*` should not be translated.

In `prmaps.utxt`:
* `HUD_LEVELNAME_*` should not be translated.
* `cpname_*` should not be translated.
* This means that the only strings that should be translated are `GAMEMODE_DESCRIPTION_`.

`prvehicles.utxt` should not be translated at all, as it is an automatically generated file.

Handling updates
---------------------

When a new string is added in `English`, it will automatically be committed to the rest of the languages in English. The contributor then translates from English to their chosen language.

If an `English` string is modified, it will not be updated in the other languages. It is up to the contributor to stay up to date with changes made to English to ensure they don't become out of date.

If translation starts on a currently un-translated language, it is recommended to start with the `English` files instead of existing translations, as they may be out of date because to the above paragraph.

Custom fonts
---------------------

If you require custom font support, please make a new thread in the [PR:BF2 Community Modding forum](http://www.realitymod.com/forum/f388-pr-bf2-community-modding) and we will guide you on what is required for your fonts to be supported ingame.
