Intro
=====

Localizations in Unturned are what provide the text seen in the menu, game and editor. Both the user interface and specific content can be translated as instructed below.

Interface
=========

You can translate the interface such as the menu, game and editor by copying the English folder found in the Localization folder and renaming it to your language. This contains many .dat files, each with several keys representing various values.

By replacing these values with the equivalent in your language the game will display them instead. Any keys not provided will be replaced with #KEY_NAME when displayed. Cases of "{#}" should be preserved in your translation, as these represent a replacement. For example, in the line Ammo: {0} the "{0}" represents the current ammo counter. The "Ammo:" text can be translated, but the "{0}" should be kept so that the value can be shown.

Note: When saving your translation be careful to explicitly mark it as UTF-8.

Content
=======

You can translate specific items/objects/vehicles/etc by copying the English.dat file found alongside the content's information and renaming it to your language. From there the process of translating is exactly the same as it is for the interface.

Testing
=======

You can test your localization by running Steam in the language you are localizing for. The folder/file name it looks for is the same as the one selected. For example, if the English language is selected the game looks for the English folder in Localizations and English.dat files in items.

If the language is not supported by Steam, or you are making one up like "Piratespeak" you can add the command line parameter +LanguageName. For example, to test the Piratespeak localization you would add +Piratespeak.
