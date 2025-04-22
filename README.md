# Basic Troubleshooting on PC/Laptop


## Table of Contents:
- [Random PC PC/Shurdown](#random-pc-restartshutdown)
- [No Display](no-display)






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


