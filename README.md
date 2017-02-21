# WinDBGtree
A cmdtree based on commands and extensions for Windows kernel debugging using WinDBG.
Windbgtree is a Microsoft WinDbg command tree that expands the set of available commands by Microsoft WinDbg, 
Windbgtree aims at making life easier for windows kernel researchers, troubleshooters and security experts with a series of debugging, incident response and memory forensics commands. 2016 Contest
Installation
You can either copy the WinDbgtree.txt file in the corresponding (x86 or x64) WinDbg folder or load it manually using the .cmdtree command such as below. 

# Example:
kd> ..cmdtree C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\windbgtree.txt


PS.: In order to get all extensions working properly, please make sure we have SwishdbgExt, DBGKit and MEX already configured.
