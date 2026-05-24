Put under R1DeltaContent/r1/addons

To disable fully just move the folder out of addons.

Adding a new titan is easy now.
Also adds 3 BlackMarket Titans as examples that can be used in game too.

NOTICE: Do not use with mods which drastically alter the game or files that this mod uses, it will be incompatible.

Make sure you have your SET file in the proper place.

NOTE the titan limit is 12 including base titans for now, as that is how many buttons the menu has.

scripts to be altered:

-Yoshi's_TitanCreator			to "create" it via my function

-classes				import the SET file

-persistent_player_data_version_299	to add your titan to Enum

-_pdef 					to add to Enum again

if using a new model:

-consts					add model as constant

-_titan_shared				add hatch model to model
