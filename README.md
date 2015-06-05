<h1>Shadow Pack of Hope</h1>
Custom modpack for use by gaming clan <i>Shadows of Hope</i>, this pack has not received permission from individual mod creators in the Minecraft community. We do not intend to redistribute or share this modpack with anyone outside of the <i>Shadows of Hope</i> community. We cannot be held responsible for any unwanted redistribution caused by the presence of this modpack on GitHub.

Otherwise, have fun!

<h2>CLIENT INSTALLATION INSTRUCTIONS</h2>
<i>Download this repository to a folder outside of the .minecraft directory.</i>

<h3>INSTALLING FORGE</h3>
1. Open your Minecraft Launcher.
	<ul>
		<li>Select new Profile.</li>
		<li>Name this profile Shadow Pack of Hope</li>
		<li>Under version, select "release 1.7.10"</li>
	</ul>
2. Start the game to download Minecraft 1.7.10.</li>
3. Once Minecraft loads, exit Minecraft.</li>
4. Right-click forge-1.7.10-10.13.3.1408-1.17.10-installer.jar
	<ul>
		<li>Select "Open With --> Java(TM) Platform SE binary"</li>
		<li>Select "Install Client"</li>
		<li>The installer will prompt you when the install is complete.</li>
	</ul>
5. Open the Minecraft launcher.
<ul>
	<li>Select the profile "Forge."</li>
	<li>Select "Edit Profile."</li>
	<li>Rename profile to "Forge1710"</li>
	<li>Check Game Directory. At the end of the list you will see ".minecraft". Change ".minecraft" to ".forge1710"</li>
<ul>

6. Check JVM Arguments.
<ul>
	<li>Delete the entire line.</li>
	<li>Add -Xmx3G (Replace 3 with your desired GB of RAM to use).</li>
<ul>

<i>We suggest a minimum of 3GB and if possible 6-8GB of RAM; <b>WARNING: DO NOT EXCEED YOUR AVAILABLE RAM	IF YOU DON'T KNOW WHAT THIS OPTION DOES, THEN DO NOT ENABLE IT - UNCHECK JVM ARGUMENTS</b></i>

7. Save the profile.
8. Start Minecraft.
9. Forge loader will begin initial setup for mods, give it time.
10. After Minecraft starts and reaches the main menu, exit Minecraft.
11. Forge installation completed, continue to mod installation.

<h3>INSTALLING THE MODS</h3>
1. Open your start menu or and insert "%appdata%"
2. Look for the directory .forge1710
3. Open .forge1710
4. Copy the config and mods folders from where you downloaded to roaming/.forge1710/
5. Allow it to overwrite both the mods and config folders.
6. Mod installation complete, you now have everything needed.

<h4>WARNING: </h4>
Upon restarting Minecraft, it will take awhile the first time to load. Strongly suggest you examine your options as they will be vastly expanded. If you create a single player world,  ensure you select advanced options and use Biomes'O Plenty for full effect of mod pack upon Survival mode.

Enjoy and have fun!  These instructions may look complicated, but they really are quite simple.  Contact me if you have any troubles.

<h2>SERVER INSTALLATION</h2>
These instructions assume you have already configured your server properly to run a Minecraft server.

1. Connect via SSH and navigate to your desired install location (ie. /home/minecraft/install)
2. Run the command "git clone https://github.com/Surumon/MC1710-SoHpack.git"
3. All the required files will be loaded from GitHub.
4. Run the installer with "java -XX:MaxPermSize=128m forge-1.7.10-10.13.3.1408-1.7.10-installer.jar".
5. Installation is complete. Run the server either from the command line or your server control panel.

<h3>SERVER INSTALLATION NOTES</h3>
If you are installing this mod pack for a server, delete the following mod jars:

- Optifine
- Dynamic Lights

Remember, you must edit your server properties to use Biomes O'Plenty (level-type: BIOMESOP).

<h2>UPDATE INSTRUCTIONS</h2>

<b>WARNING: REMEMBER TO ALWAYS DELETE THE OLD VERSIONS OF MODS. OTHERWISE YOU WILL HAVE CONFLICTING ISSUES/CRASHES. YOU HAVE BEEN WARNED!</b>

<h3>Client Side (Full Wipe):</h3>
1. Ensure the server is running the newer version.
2. WinXP: Start --> Run --> %appdata% // Win7: Type %appdata% into "Search programs and files"
3.This is your roaming directory, go to where you told Forge to have it's MC Folder. (If you followed my directions it's Roaming/.forge1710)
4. Delete the directories mods and config
5. Download the mods and config folders again.

<h3>Client Side (Selective Update)</h3>
1. Ensure the server is running the newer version.
2. See changelog.md and read the changes.
3. Delete updated mods from the mods folder.
4. Install the specific mods listed.
5. Update the specific config files listed.

<h3>Server Side Updates</h3>
1. Stop your Minecraft Server.
2. Open your SSH client and navigate to your Minecraft installation (ie. /home/minecraft/install)
3. Run the command "git pull".
4. Start the server.

<h2>CREDITS</h2>
	Ars Magica 2 - Mithion - http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1292222-ars-magica-2-version-1-4-0-008-updated-february-6
	Mine & Blade: BattleGear2 - http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1291267-mine-blade-battlegear-2-bullseye-1-0-8-0#BugsIssues
	AgriCraft - InfinityRaider - http://forum.feed-the-beast.com/threads/1-7-10-agricraft.50964/
	the AnimationAPI - thehippomaster21 - http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1289836-animationapi-animate-your-entities-v1-2-3
	Antique Atlas - Hunternif - http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1292324-antique-atlas
	AppleCore - squeek502 - http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/2222837-applecore-an-api-for-modifying-the-food-and-hunger
	Automagy - Tuhljin - http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/wip-mods/2125369-tc4-addon-automagy-v0-24-1-automation-and
	Battle Towers - AtomicStryker - http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1275201-atomicstrykers-battle-towers
	Baubles - Azanor - http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1294623-baubles-1-1-1-0-updated-2015-3-2
	Bibliocraft - Nuchaz - http://www.bibliocraftmod.com/ or https://github.com/Nuchaz/BiblioCraft
	Binne's Mods - Binne - http://minecraft.curseforge.com/mc-mods/223525-binnies-mods
	Biomes O' Plenty - Glitchfiend - http://www.minecraftforum.net/forums/mapping-and-modding/minecraft-mods/1286162-biomes-o-plenty-over-75-new-biomes-plants-and-more<
	Botania - Vazkii - http://botaniamod.net/
	BuildCraft - The Buildcraft Team - http://www.mod-buildcraft.com/

Full credits to be finished at a later time/date.  It's a lot to do.
