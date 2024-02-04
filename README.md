# viva-new-vegas-wabbajack-test
This is an attempt to convert Viva New Vegas into a Wabbajack mod list. 

Now supports the Viva New Vegas - Extended, updated February 4th 2024.

# This is incomplete, and the game will not run correctly without performing these steps:
## After Wabbajack finishes installing:
	1. Open Included Mod Organizer 2 as Administator
	2. Select the version of Viva New Vegas you would like to play (Base or Extended)
	2. Copy the NVHR folder from New Vegas Heap Replacer into New Vegas's Data folder
	        You can do this by double clicking the mod in Mod Organizer, clicking Open Mod in Explorer, then copying and pasting into New Vegas's Data folder, usually in /Steam/steamapps/common/Fallout New Vegas/Data. 
	3. Open Included Mod Organizer 2 as Administator
	4. Run the "Ultimate ESM Fixes" program through Mod Organizer
	    	Set output folder to the "Ultimate Edition ESM Fixes" folder in the /mods/ folder of your install.			
	5. Run the "FNV BSA Decompressor" program through Mod Organizer
	    	Set output folder to the "FNV BSA Decompressor" folder in the /mods/ folder of your install.
	6. Run the 4GB FNV Patch through Mod Organizer
	7. All set. Should be able to launch the game through the "New Vegas" option. 
	
	Note: You will have to do this for both of the profiles if you wish to switch between them. 


# To-Do
	Somehow automate the running of FNV BSA Decompressor and the running of the 4GB patch through Mod Organizer. 
	    Maybe some type of Python script or Powershell Script?
	
	Temporarily automate copying NVHR from the mods folder to the Data folder. 
		More permanent solution would be somehow successfully installing NVHR with Root Builder maybe?
	    Add Uninstall option script to remove NVHR from the Data folder of New Vegas.
	Automatically grab the iNumHWThreads= value on the users system and update the falloutcustom.ini automatically.
	Test Epic Games.
	Test GOG.
	Direct users to Performance and Stability Guide
	Figure out to do with Viva New Vegas Base + Extended and Iron Sights Aligned. Maybe two separate mod folders for the same mod?
	Potentially add Mojava Express Guide? Haven't looked at it.
	



