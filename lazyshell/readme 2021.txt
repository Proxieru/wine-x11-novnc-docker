Lazy Shell: Updated Edition, modified by Yakibomb, from 2019-2021
Lazy Shell, created by Omega & giangurgolo, from 2007-2013

"Lazy Shell: Updated Edition" is an unofficially endorsed build by the original authors. 
It was built from the original source code of Lazy Shell v3.19.0.

--------------------

Original upload site (RHDN)
https://www.romhacking.net/utilities/1486/

This program's source code (GitHub)
https://github.com/Yakibomb/LAZYSHELL-UPDATED/tree/master

--------------------

This comes with four files:

"LAZYSHELL_UPDATED_EDITION.exe"
The updated Lazy Shell -- Super Mario RPG editor.

"SMRPG Documents"
The folder with a lot of hex and ASM data. Used for more advanced purposes.

"HackingGuide.doc"
Giangurgolo (one of Lazy Shell's original authors) released an outline for making any hack with this editor.

"readme 2021.txt"
This file you're reading.

--------------------

LAZY SHELL: UPDATED EDITION CHANGELOG 
Latest Build: September 2021

==============================
=======V1.3.1 CHANGELOG=======
==============================
MAIN
- Updated all icons to those of Lazy Shell 4.0.0
- File path for ROM now shows just the ROM file's name. (Click the ROM file name to reveal full path)

ANIMATIONS
- Added Weapon Timed-Hit Sounds (for when a weapon is timed correctly)
- Added Character Weapon Scripts (for when characters draw near to attack a monster)

==============================
=======V1.3.0 CHANGELOG=======
==============================
ANIMATIONS
- Added documentation of Ally button inputs, used by opcodes CC, CD, CE, CF, D0, D1, D2, D3, D4, D8.

ATTACKS
- Removed being able to edit the timings for certain ally spells. (i.e. Super Jump, Bowser Crush, etc)
- In place of that, added ability to change the timing of any ally spell and their damage properties.

==============================
=======V1.2.8 CHANGELOG=======
==============================
ANIMATIONS
- Changed length displayed for commands A7 and DB.

==============================
=======V1.2.7 CHANGELOG=======
==============================
DIALOGUES
- Resolved Battle Menu GFX editor displaying the wrong tiles.

==============================
=======V1.2.6 CHANGELOG=======
==============================
ANIMATIONS
- At 0xD5: Added formation position #, fixed bug
- At 0x00: Removed "use palette row 4", added "Palette Row #" value
- A5 0x96: Battle Messages can now be set above 6

MONSTERS
- Clearing a Monster's Stats will reset win items and Yoshi cookie to the correct value

==============================
=======V1.2.5 CHANGELOG=======
==============================
EVENTS
- Changed "$70Ax = $7xxx" to "$70Ax = $7000" due to mislabel
- Increased length of HEX display at the bottom
- Added "(NOT including {xx})" to randomized number codes.
- Changed description of 3A and 3B commands to be more accurate

FORMATIONS
- Clearing a formation will set the event # to 102 (from 0) and music to CURRENT (from Normal)

==============================
=======V1.2.4 CHANGELOG=======
==============================
MAIN
- Increased height of search box results

ANIMATIONS
- Fixed bug with monster behavior scripts

ITEMS
- Added hex editor next to item index

==============================
=======V1.2.3 CHANGELOG=======
==============================
MAIN
- Added original SMRPG Documents by giangurgolo, updated by Yakibomb

ANIMATIONS
- At 0xD5: Fixed Summon monster display
- Added numerals next to opcodes

EVENTS
- Removed numerals from sound lists

==============================
=======V1.2.2 CHANGELOG=======
==============================
ANIMATIONS
- Added new scripts: Faint, Run Away and Victory (under Monster Behavior #1-3)

EVENTS
- To Open menu commands: Added "close menu and refresh VRAM" and now script displays what menu/event will run

==============================
=======V1.2.1 CHANGELOG=======
==============================
EVENTS
- Switched Memory commands $7xxxx = $7xxxx because it was confusing to read

==============================
=======V1.2.0 CHANGELOG=======
==============================
AUDIO
- Changed names of event sounds and battle sounds

ANIMATIONS
- At 0xD5: Added undocumented Summon Monster
- Added ability to select and edit unused DUMMY spells for allies
- Changed the ability to select sounds and music using an index number
- Removed the numbers from the left of the sound list (for faster searching)
- At 0x00: added undocumented "behind all sprites" and "overlap all sprites" properties

EVENTS
- Fixed bug where "If Memory $704x [x @ 7000] bit {xx} clear..." auto-jumped to another command
- Fixed bug where "Shadow On" was unselectable
- Added undocumented 3A and 3B commands: Jump to if object is less than x tiles close to Mario

==============================
=======V1.1.0 CHANGELOG=======
==============================
EVENTS
- Switched joypad commands descriptions in category list
- Updated parameters for "Display pre-game intro title..." to display correctly in the editor script

===========================
=======V1.0.0 RELEASE=======
===========================
MAIN
-Changed file icon for LazyShell
-Changed the ABOUT LAZY SHELL... to this editor's changelog

ANIMATIONS
- Added ability to edit Flower Bonus Messages, Toad's Battle Tutorial and Weapon Miss Sounds
- Added ability to select and edit unused DUMMY spells for allies

EVENTS
- Added undocumented bit 7 of Run Background Event... as "Run as second script"
- Added move script thread commands under category "Events"
- Added undocumented commands to walk and transfer to Memory $7016-1B
- Added undocumented "Play sound (ch4.5.) ..."

LEVELS
 - Added undocumented commands {B2,b4} and {B3,b0} as "Can't enter doors" and "Can't walk up stairs".

ITEMS
 - Added new attribute: "Add stats (item)"

WORLD MAPS
- Added ability to view (not edit) Mario's map sprite