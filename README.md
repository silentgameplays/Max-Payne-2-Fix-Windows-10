# Max-Payne-2-Fix-Windows-10
# NB! The creator of this fix is not responsible if something will go wrong during install,or for any issues that arise on your OS/hardware.This fix is distributed under GPL 3.0 license.This tutorial is meant for enthusiasts,tinkerers and gamers who want the the game to work and are not affraid to take the risk of learning some new stuff in the process.

Max Payne 2-Fix-Windows-10
FPS Fix:

0. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play and .NET 3.5 Framework support

1. Install Max Payne 2

2. Download files from this repository

3. Extract files

4. Copy/Paste into C:\Program Files (x86)\Steam\steamapps\common\Max Payne 2 The Fall of Max Payne

# NB for Dual GPU's Laptops only!

1. Download everything extract.

2. Copy all files from Reshade Dual GPU's Laptops folder C:\Program Files (x86)\Steam\steamapps\common\Max Payne 2 The Fall of Max Payne

3. Go to your NVIDIA Control Panel>3D Settings>Global find the preferred GPU and set it to NVIDIA

4. Enjoy

# (Optional) Bonus maximize difficulty settings via registry
0. Launch the game at least once and play the tutorial level for a bit.Exit
1. Start Menu->Run and type in regedit. Press Enter. 
2. Go to HKEY_CURRENT_USER->Software->Remedy Entertainment->Max Payne 2. 
3. Click on the 'Game Level' folder, and some items will appear on the right side of the screen. 
4. Right-Click and select New-DWORD Value 
5. Double-Click on the entry you just made and set the value to 1. 
6. Rename the entries to the following:
* hell for Dead On Arrival mode
* nightmare for Hard-Broiled mode
* timedmode for New York Minute mode

# Added 60FPS support for 1080p Thirteen AG patch.
1. Download and extract into your C:\Program Files (x86)\Steam\steamapps\common\Max Payne 2 The Fall Of Max Payne

# Max Payne 2 Linux Fix with 60 FPS lock
1. Install Mangohud for yout distro
2. Download Max Payne 2 Fix Linux from here or Thriteen AG's official repository,extract to game folder.
https://thirteenag.github.io/wfp#mp2
3. Go to Steam>Max Payne 2:The Fall Of Max Payne>Compatibility>General>Launch Options
4. WINEDLLOVERRIDES="d3d8=n,b" MANGOHUD_CONFIG="fps_limit=60,no_display" mangohud %command%
5. Enjoy the game
6. At the time of testing Steam Protov version was 9.0.1

# Enjoy!
# Credit goes to Thirteen AG for wrapper and .ini FPS limiter creation visit him for more goodies:https://thirteenag.github.io/wfp
# Credit for compilation and testing on latest Windows 10 builds goes to silentgameplays



