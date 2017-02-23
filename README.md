# WinDBGtree
=============

WinDBGtree is a WinDbg command tree that expands the set of available commands by Microsoft Windows Debugger aka WinDBG.
Windbgtree comes up making life easier for Windows kernel researchers, Windows Internals troubleshooters and also security experts.

This WinDBGtree has been created by Vagner Pilar @vagnerpilar (Twitter) – Feel free to reach me out on https://twitter.com/vagnerpilar asking for more features, offering to contribute and any kind of feedback.

# Installation
===============
You can copy the WinDbgtree.txt file in the corresponding (x86 or x64) WinDbg folder and load it manually using the .cmdtree command such as below or adding the path on the WinDBG shortcut.

# Example:
===========

```
kd> .cmdtree C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\windbgtree.txt
```

PS.: In order to get all extensions working properly, please make sure we have SwishdbgExt, DBGKit, MEX, Wdbgark and Patterns already configured.

```
SwishdbgExt - https://github.com/comaeio/SwishDbgExt (Thanks to Matt Suiche (@msuiche))
DBGkit - http://www.andreybazhan.com/dbgkit.html (Kuddos to @AndreyBazhan)
MEX - https://www.microsoft.com/en-us/download/details.aspx?id=53304 (kuddos to Microsoft)
WinDBG Anti-RootKit Extension - https://github.com/swwwolf/wdbgark (Kuddos to Vyacheslav Rusakoff @@swwwolf)
Patterns Debugger Extension DLL - http://www.patterndiagnostics.com/patterns-extension
```
