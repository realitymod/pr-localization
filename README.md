Project Reality: BF2 Community Localization
---------------------

https://github.com/realitymod/pr-localization


This repository is for openly maintaining the [Project Reality: BF2](http://www.realitymod.com) localization files for all the different languages.

For community contributions, please make a make a **fork** and submit a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).

Editing guide
---------------------

We recommend contributors use [Notepad++](https://notepad-plus-plus.org/) to edit the .utxt files.

<p align="center">
<img src="http://media.realitymod.com/misc/prl18n-notepad-guide.jpg" alt="Example" title="Example" width=700 height=250 />
</p>

It is helpful to have View > Show Symbol > Show White Space and TAB enabled in Notepad++.

Testing translations
---------------------

First, run `check-localization.exe` which will check for some common mistakes made in localization files. Fix any errors it detects, otherwise continue to testing ingame.

To test your changes in the current version of PR:BF2, just edit the necessary files located in:

>`<PR Install Dir>/mods/pr/localization/<language>`

Please make sure you have tested your changes both in the launcher and ingame, and have confirmed they are working correctly **prior to submitting a pull request!**

If there are characters missing, or your text does not display, it is most likely an issue with the font used. See below for more information regarding custom fonts.

*Note: Change the language used in PRLauncher > Options > Global > Language*

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

If you require custom font support, please make a new thread in the [PR:BF2 Community Modding forum](https://www.realitymod.com/forum/forumdisplay.php?f=388) and we will guide you on what is required for your fonts to be supported in the launcher and/or ingame. You can also try for yourself with the second part of [this tutorial](https://www.realitymod.com/forum/showthread.php?t=140120) on how to make BF2 Fonts.

Contributors
---------------------
* Chinese - [jerro1105](https://github.com/jerro1105), [Wangrenze9788](https://github.com/Wangrenze9788)
* Dutch - [[R-DEV]Mineral](https://github.com/WouterJansen)
* English - [PR Team](https://github.com/realitymod)
* French - [Grey-Echo](https://github.com/Grey-Echo)
* German - [PrStrategos](https://github.com/PrStrategos), [SINE](https://github.com/SINE)
* Japanese - [ltakeshi](https://github.com/ltakeshi)
* Polish - [Darekdeo](https://github.com/darekdeo)
* Russian - [[R-DEV]Tema567](https://github.com/art567)
* Spanish - [Leg-Ion](https://github.com/leg-ion)
* Ukrainian - [Lyttym](https://github.com/Lyttym) 
* Indonesian - [TommyFederal](https://github.com/TommyFederal) 
* Brazilian Portuguese - [ParacetamoL217](https://github.com/ParacetamoL217), [Paracetamol](https://github.com/ParacetamoL217), [Gabo](https://github.com/GaboV3), [Concani](https://github.com/concani), [Schultz](https://github.com/Vapex55), [GuilFe](https://github.com/GuilFe)
