# Italian WoW 1.12.1
Backport MoP italian localization to create an Italian vanilla client. Everything clientside is translated except spells and maps.
Most of the localized text is 1:1 copied from MoP, however there is about 500 texts that use own translation
due to removal of several strings between vanilla and MoP.

If you are interested in seeing what strings blizzard removed, look for the lines with --custom.
For changes made to the italian MoP localization to be more like vanilla, look for lines with --changed.

This client wasn't created by a native speaker, so if you spot any translation issues, please create an issue.

Do note that this repository itself does not contain the translated sounds or DBC files.
If you want those files, they can be found packaged as a .MPQ in the Setup section below.

Video showcasing the Italian vanilla localization:

[![Italian 1.12.1](https://img.youtube.com/vi/3D-ZW84d3ds/0.jpg)](https://www.youtube.com/watch?v=3D-ZW84d3ds)

### Setup
Strings, sounds and DBCs packaged in MPQ, also includes localized intro video:
https://drive.google.com/uc?export=download&id=1CyqG8E1Ovq2DQzLwh-2AQAEVnHaP6D_s
Do note that the strings included in the above download do not include any comments.

Installation: Put it into your root WoW folder (where wow.exe is located) and click yes when asked to replace files. Boot up WoW and enjoy vanilla in Italian.

### F.A.Q: Is it save to run? 
It is safe to run on any vanilla realm which accepts the Russian 1.12.1 client. There is no realm that blocks the Russian vanilla client, so the Italian vanilla client should be safe to run on any server.

### Why does the client crash at startup? 
You have to run it with the wow.exe included in the above download, otherwise the original wow.exe will prevent you from loading the custom interface files.

If you want quests to be translated to Italian on any servers, highly suggest using:
https://github.com/Daribon/QuestTranslator

For serverside texts such as items and NPC names, use Mangos-Zeros Italian DB repository:
https://github.com/MangosExtras/MangosZero_Localised/tree/master/Translations/Italian

### Thanks
Special thank you to AzerothShard for Italian sounds and Wowruru project for providing Russian sounds which helped speed up the sorting of sounds.