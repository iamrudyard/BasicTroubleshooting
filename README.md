# Basic Troubleshooting on PC/Laptop


## Table of Contents:
- [Windows and MS Office Activator]([#windows-and-ms-office-activator](url))
- [Random PC PC/Shurdown](#random-pc-restartshutdown)
- [No Display](#no-display)
- [Bypass Microsoft Account during Installation](#bypass-microsoft-account-during-installation)




### Windows and MS Office Activator
- Step 1
Copy the code below:
```
irm https://get.activated.win | iex
```
- Step 2 
Open Windows Powershell [ Run as Admin] and Paste the code. Click Yes.
- Step 3
In Command Propmpt Menu Selction,
Select 1 for Windows Activation
Select 2 then 1 for permanent activation of Any Office version

### Random PC Restart/Shutdown
- Step 1  
Control Panel > Hardware and Sound > Power Options > Edit Poweer plan > Change advanced power settings > PCI Express > Turn Off

- Step 2  
Open CMD (RUn as Admin) and type this:
```
powercfg -h off
```
 then restart the PC

- Step 3  
Open CMD (RUn as Admin) > type:
```
sfc /scannow 3.1 type: dism /online /cleanup-image /restorehealth 3.2 then Restart the computer.
```


### No Display
- Step 1
  Remove the RAM and clean with eraser. If still no display, try step 2.  
- Step 2
  Remove Storage devices. 


### Bypass Microsoft Account during Installation
- Step 1
Press Shift+F10 to open command propmt.
- Step 2
Type in the command propmt.
```
OOBE\BYPASSNRO
```

