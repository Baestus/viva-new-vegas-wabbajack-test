# viva-new-vegas-wabbajack-test
This is an attempt to convert Viva New Vegas into a Wabbajack mod list. 

Now supports the Viva New Vegas - Extended, updated February 4th 2024.
Does not currently support the most up to date version of Viva New Vegas. 
# This is incomplete, and the game will not run correctly without performing these steps:
## After Wabbajack finishes installing:
	1. Run the "FNV BSA Decompressor" program through "_FNV BSA Decompressor" folder 
	    	Set output folder to the "_FNV BSA Decompressor" folder in the /mods/ folder of your modlist instal
	2. Copy the "NVHR" folder from New Vegas Heap Replacer into New Vegas's Data folder
	        You can do this by double clicking the mod in Mod Organizer, clicking Open Mod in Explorer, then copying and pasting the "NVHR" folder into New Vegas's Data folder, usually in /Steam/steamapps/common/Fallout New Vegas/Data. 
	3. Run the 4GB FNV Patch through Mod Organizer
	4. All set. Should be able to launch the game through the "New Vegas" option. 	


# To-Do
	Somehow automate the running of FNV BSA Decompressor, ESM Fixes, and the running of the 4GB patch through Mod Organizer. 
	    Maybe some type of Python script or Powershell Script? Linux version uses a Python script for 4GB Patcher. 
	Temporarily automate copying "NVHR" from the mods folder to the Data folder. 
		More permanent solution would be somehow successfully installing NVHR with Root Builder maybe?
	    Add Uninstall option script to remove "NVHR" from the Data folder of New Vegas.
	Test Epic Games.
	Direct users to Performance and Stability Guide. Automate if possible.
	Figure out how to get rid of Improved AI YUP Patch and Iron Sights Aligned from the bottom of Visuals in the Extended Profile.
		Each profile now has its own separate folder for the mod, "Iron Sights Aligned" and "Iron Sights Aligned - Anniversary Anim Pack Compatible". 
		Not sure why Wabbajack wants to put the profile specific disabled mods at the bottom of the load order, but it could cause confusion in the future.
	Potentially add Mojave Express Guide? Haven't looked at it.
	Add the pre-install checklist from the guide.



