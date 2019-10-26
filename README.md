DV-DS-CompatPacks ["Aetherius" - Compatiblity Patches for Various mapsets]

- Includes compatiability patches and PK3 files for the following wads/etc. Though keep in mind some of these are currently incomplete.
	- Knee Deep in ZDoom (loaded as a subfolder)
	- The City of the Damned: Apocalypse (loaded as a subfolder)
	- The Ultimate Torment N' Torture (loaded as a subfolder)

HOW TO INSTALL / RUN / ETC:

 - Important - Make absolutely sure you got DV-DS-ComboPack [@ https://github.com/LordMisfit/DV-DS-ComboPack ] working right before you do anything here. Refer to that repository's README.md file for more information.

 - Installing 1 - Make sure you unzip the entire "DV-DS-CompatPacks3" folder inside the zip file to your designated GZDoom folder. Do not try to install the subfolders within into "DV-DS-ComboPacks" or into your main GZDoom folder, or you've done flapped it up and have to do everything up to this point on both repositories over again. :V
 - TL;DR: So basically make sure "DV-DS-ComboPacks" & "DV-DS-CompatPacks3" are seperate subfolders in your main GZDoom folder. :P

 - Running - 1. There is no launcher packed for use with DV-DS-CompatPacks3, you'll have to rely on command lines for now. My general method is to create a batch [.bat] file and name it something you'll remember. Remember you can right click a .bat file and "edit" them to change the command line used inside.

 - Running - 2. To run KDIZD w/ "Aetherius" Command line: "start gzdoom.exe -iwad doom2.wad -file "DV-DS-ComboPack" "DV-DS-CompatPacks3/KDIZD" +hud_scale 0 exit" 

 - Running - 3. To run The City of the Damned: Apocalypse w/ "Aetherius" Command line: "start gzdoom.exe -iwad doom2.wad -file "DV-DS-ComboPack" "DV-DS-CompatPacks3/TCOTD2" +hud_scale 0 exit" 
 - Note: It's only one level, and Flora is the only playable class in this one, but boy did this patch take a while to make, since I actually did a bunch of ACS modifying for the level itself and things don't exactly work 1 to 1 how they do in the original version, plus Flora will actually put her two cents in for all the notes and events that happen in this one. >.>

 - Running - 4. To run The Ultimate Torment N' Torture w/ "Aetherius" Command line: "start gzdoom.exe -iwad doom2.wad -file "DV-DS-ComboPack" "DV-DS-CompatPacks3/TUTNT" +hud_scale 0 exit" 
 - Note: Flora is the only playable class in this one as well.

 - ABOUT LegenDoomLite: Can be added to any mode [or game type or even normal Doom1/2] essentially by adding "DV-DS-CompatPacks/LegenDoomLite" into the command line as the last file loaded. This one does NOT have to be loaded as a seperate mod from the above and is basically compatible with any of them and thensome. :V
