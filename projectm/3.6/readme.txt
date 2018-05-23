Project M Stage Annotation Project

The goal of this end of the stage annotation project is less focused on bases for original stages.
Rather, the P:M annotated stages currently focus on making 1:1s of tournament stages.

There are edits from the original P:M stages beyond the annotations.
These are all made to increase customizability and provide better bases. They do not affect gameplay in any way.
In the interest of transparency, here are all the edits made thus far:

Global Changes:
- Most stages have been reorganized to facilitate custom edits. ModelDatas have been reordered and extra ModelDatas not loaded by the game have been removed.
- All stages use ExtendedLZ77 compression on ARC 2 and their effects file. This decreases their filesize.

STGBATTLEFIELD (Brawl Battlefield):
- Changed internal name ("STGBATTLEFIELD" -> "STGBATTLEFIELDBRAWL3.6" on original, "STGBATTLEFIELD" -> "STGBATTLEFIELD3.6" on empty)

STGBATTLEFIELD_Z (Melee Battlefield):
- Changed internal name ("STGBATTLEFIELD" -> "STGBATTLEFIELDMELEE3.6")
- Fixed "Front" to use proper material

STGDOLPIC (Delfino's Secret):
- Fixed misspelling of stage name in the original credits MSBIN ("Delphino" -> "Delfino")
- Unbound main platform collision object from non-existent object

STGFAMICOM (Fountain of Dreams):
- Fixed multiple objects to use "gr2_" transparency, fixing issues where players would always render in front of certain transparent objects
- Unbound top platform's collision

STGKART_Z (Bowser's Castle Competitive)
- Added ModelData[10] as it can be optionally loaded in game
- Downscaled Target texture to save space
- Fixed PokeTrainer00 model not being accessible by the game (preserves vBrawl compatibility)
- Unbound main platform collision object

STGMADEIN (Wario Land):
- Changed internal name ("STGDXFINAL" -> "STGWARIOLAND")
- Changed effect folder name ("ef_StgDxFinal" -> "ef_StgWarioLand")
- Unbound main platform collision object