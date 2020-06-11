# Max-Payne-2-Fix-Windows-10
Max Payne 2-Fix-Windows-10
FPS Fix:

0. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play and .NET 3.5 Framework support

1. Install Max Payne 2

2. Download files from this repository

3. Extract files

4. Copy/Paste into C:\Program Files (x86)\Steam\steamapps\common\Max Payne 2 The Fall of Max Payne


# (Optional) Bonus maximize difficulty settings via registry
0. Launch the game at least once and play the tutorial level for a bit.Exit
1. Start Menu->Run and type in regedit. Press Enter. 
2. Go to HKEY_CURRENT_USER->Software->Remedy Entertainment->Max Payne. 
3. Click on the 'Game Level' folder, and some items will appear on the right side of the screen. 
4. Right-Click and select New-DWORD Value 
5. Double-Click on the entry you just made and set the value to 1. 
6. Rename the entries to the following:
* hell for Dead On Arrival mode
* nightmare for Hard-Broiled mode
* timedmode for New York Minute mode
