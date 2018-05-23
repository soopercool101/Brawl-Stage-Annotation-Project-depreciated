Vanilla Brawl Stage Annotation Project

The goal of this end of the Stage Annotation Project is to document out the gimmicks and quirks of vanilla Brawl stages.
The end goal of this is to make using and repurposing elements of Brawl stages for custom stages easier.

There are two folders: Empty and Original

The Empty folder contains all current annotated stages, precompressed, with only the base components needed to control the gimmicks of the original stage.

The Original folder contains all currently annotated base stages from vBrawl.

There are some minor bugfixes and changes from the original vBrawl stages beyond just the annotations.
These are all made to increase customizability and provide better bases. They should not affect gameplay in any way.
In the interest of transparency, here are all the edits made thus far:

Global Changes:
- All stages have had their compression algorithm changed from LZ77 to ExtendedLZ77. This decreases their filesize.

75m:
- Changed the texture filtering on the StgDonkey_Score_800 model in ModelData[10] from Linear to Nearest (Now matches the rest of the stage correctly)