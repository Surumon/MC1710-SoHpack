# MC1710-SoHpack
Dev directory for custom mod pack I am working on - Not for general distribution.

In short:
THIS MOD IS NOT FOR REDISTRIBUTION ON FEED THE BEAST OR ANY OTHER MINECRAFT MOD PACK SHARING SERVICE.
THIS MOD PACK IS FREE FOR PERSONAL OR PRIVATE USE.
USE AT YOUR OWN RISK - I AM NOT RESPONSIBLE FOR ANY DAMAGES OR LEGAL ACTION TAKEN AGAINST YOU FOR MISUSE OF THIS PACK.

Otherwise, have fun!

== INSTALLATION INSTRUCTIONS ==

Download all these files to a separate location.


---- INSTALLING FORGE ----

Open your Minecraft Launcher.
Select new Profile.
Name this profile MC1710.
Under version, select "release 1.7.10"
Start the game to download Minecraft 1.7.10.
Once Minecraft loads, exit Minecraft.

Right-click forge-1.7.10-10.13.3.1408-1.17.10-installer.jar
Select "Open With --> Java(TM) Platform SE binary"
It will take a moment to open the installer.
Select "Install Client"
The installer will prompt you when the install is complete.

Open the Minecraft launcher.  Select the profile "Forge."
Select "Edit Profile."
Rename profile to "Forge1710"
Check Game Directory.
At the end of the list you will see ".minecraft"
Change ".minecraft" to ".forge1710"

Check JVM Arguments.  Delete the entire line.
Add -Xmx3G (Replace 3 with your desired GB of RAM to use).
(I suggest a minimum of 3GB and if possible 6-8GB of RAM; WARNING: DO NOT EXCEED YOUR AVAILABLE RAM
	IF YOU DON'T KNOW WHAT THIS OPTION DOES, THEN DO NOT ENABLE IT - UNCHECK JVM ARGUMENTS).

Save the profile.
Start Minecraft.
Forge loader will begin initial setup for mods, give it time.
After Minecraft starts and reaches the main menu, exit Minecraft.
Forge setup complete, continue to installing mods.

---- INSTALLING THE MODS ----

Open your start menu or and insert "%appdata%"
Look for the directory .forge1710
Open .forge1710
Copy the config and mods folders from where you downloaded to roaming/.forge1710/
Allow it to overwrite both the mods and config folders.
Mod installation complete, you now have everything needed.

WARNING: 
Upon restarting Minecraft, it will take awhile the first
time to load. Strongly suggest you examine your options as they
will be vastly expanded. If you create a single player world, 
ensure you select advanced options and use Biomes'O Plenty for
full effect of mod pack upon Survival mode.

Enjoy and have fun!  These instructions may look complicated,
but they really are quite simple.  Contact me if you have any
troubles.

== UPDATING THE MOD PACK ==

WARNING: REMEMBER TO ALWAYS DELETE THE OLD VERSIONS OF MODS.
		OTHERWISE YOU WILL HAVE CONFLICTING ISSUES/CRASHES.
		YOU HAVE BEEN WARNED!

Client Side (Full Wipe):
1) Ensure the server is running the newer version.
2) WinXP: Start --> Run --> %appdata% // Win7: Type %appdata% into "Search programs and files"
3) This is your roaming directory, go to where you told Forge to have it's MC Folder.
	(If you followed my directions it's Roaming/.forge1710)
4) Delete the directories mods and config
5) Download the mods and config folders again.

Client Side (Selective Update)
1) Ensure the server is running the newer version.
2) See changelog.txt and read the changes.
3) Update the specific mods listed.
4) Update the specific config files listed.

Server Side Updates:
Same as above, but I suggest you follow the Client Side (Selective Update)
as this will allow you to update the key files with less hassle on upload times.

"Help, I didn't ensure the server was running the new update."
You'll have to hunt down the mods that got updated in the changelog.md and
download their last versions PRIOR to the ones listed in the update.

Example:
Pack updated to Hardcore Ender Expansion 1.8.1 but the server isn't updated.
You need to download Hardcore Ender Expansion 1.8.0 for Minecraft Forge 1.7.10 from their website.

== SERVER INSTALLATION NOTES ==

NOTICE:

If you are installing this mod pack for a server, delete the following mod jars:

- Optifine
- Dynamic Lights

Remember, you must edit your server properties to use Biomes O'Plenty (level-type: BIOMESOP).

== CREDITS ==

Ars Magica 2 - Mithion - http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1292222-ars-magica-2-version-1-4-0-008-updated-february-6
Mine & Blade: BattleGear2 - http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1291267-mine-blade-battlegear-2-bullseye-1-0-8-0#BugsIssues

Full credits to be finished at a later time/date.  It's a lot to do.
