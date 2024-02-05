# viva-new-vegas-wabbajack-test
This is an attempt to convert Viva New Vegas into a Wabbajack mod list. 

Now supports the Viva New Vegas - Extended, updated February 4th 2024.

# This is incomplete, and the game will not run correctly without performing these steps:
## After Wabbajack finishes installing:
	1. Open Included Mod Organizer 2 as Administator
	2. Select the version of Viva New Vegas you would like to play (Base or Extended)
	3. Copy the NVHR folder from New Vegas Heap Replacer into New Vegas's Data folder
	        You can do this by double clicking the mod in Mod Organizer, clicking Open Mod in Explorer, then copying and pasting into New Vegas's Data folder, usually in /Steam/steamapps/common/Fallout New Vegas/Data. 
	4. Open Included Mod Organizer 2 as Administator
	5. Run the "Ultimate ESM Fixes" program through Mod Organizer
	    	Set output folder to the "Ultimate Edition ESM Fixes" folder in the /mods/ folder of your install.			
	6. Run the "FNV BSA Decompressor" program through Mod Organizer
	    	Set output folder to the "FNV BSA Decompressor" folder in the /mods/ folder of your install.
	7. Run the 4GB FNV Patch through Mod Organizer
	8. All set. Should be able to launch the game through the "New Vegas" option. 
	


# To-Do
	Somehow automate the running of FNV BSA Decompressor and the running of the 4GB patch through Mod Organizer. 
	    Maybe some type of Python script or Powershell Script?
	
	Temporarily automate copying NVHR from the mods folder to the Data folder. 
		More permanent solution would be somehow successfully installing NVHR with Root Builder maybe?
	    Add Uninstall option script to remove NVHR from the Data folder of New Vegas.
	Automatically grab the iNumHWThreads= value on the users system and update the falloutcustom.ini automatically.
	Test Epic Games.
	Test GOG.
	Direct users to Performance and Stability Guide.
	Figure out how to get rid of Improved AI YUP Patch and Iron Sights Aligned from the bottom of Visuals in the Extended Profile.
		Each profile now has its own separate folder for the mod, "Iron Sights Aligned" and "Iron Sights Aligned - Anniversary Anim Pack Compatible". 
		Not sure why Wabbajack wants to put the profile specific disabled mods at the bottom of the load order, but it could cause confusion in the future.
	Potentially add Mojave Express Guide? Haven't looked at it.
	



