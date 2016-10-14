Intended for Windows 10. 

Sets `ShowTaskViewButton` = 1, a registry key at HKCU:\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced.

This key turns on/off the Win10 virtual desktops taskbar shortcut. 
My school disabled this for some reason on lab machines. 
I run this script each time I log in. (Changes are lost on log-off, so no permament change! :P)

**Goal**: Write a chef cookbook to do this instead, along with a script to install chef if needed.