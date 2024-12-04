```
(R) IBM XGA-2/Nth Double Edge Windows NT 3.5/3.51 Video Device Driver
This is a fork of Ryan Alswede's IBM XGA-2 Windows NT 4.0 Video Device driver.
Copyright (C) 2024
Developed by Christian Holzapfel & Ryan Alswede
All Rights Reserved
---------------------------------------------------------------------
Release 12/04/2024                            christian@holzapfel.biz

SUPPORTED MODES:
 XGA-2 | Double Edge Modes------
   Resolution  Number   Refresh
   Pixels      Colors   Hz
   -----------------------------
   640x480      256     60
   640x480      256     72

   800x600      256     56
   800x600      256     60
   800x600      256     72

   1024x768     256     60
   1024x768     256     70

   640x480      65536	60
   640x480      65536	73

   800x600      65536   60
   800x600      65536   70
   800x600      65536   72
   800x600      65536   77

   1024x768*    65536   60
   1024x768*    65536   70
   ------------------------------
                Requires 2MB Card

INSTALL NOTES:
Sorry, no OEMSETUP.INF.
You have to copy over the two files from this driver's "install" directory to
Drive:\Windows\System\xga.dll
Drive:\Windows\System\drivers\xga.sys
NT won't let you replace those files while they are in use, so if you have the stock XGA2
driver loaded already, you have to find a way:
- Boot from a DOS floppy (if you're on a FAT partition) and copy over
- Install the generic VGA driver, then replace the XGA files
- Or go any other way that fits your needs.


KNOWN ISSUES:
When testing modes between 256 colors and 65536 colors, the color of the GUI can become out of sync.
This will correct itself once you choose and apply your final color and reboot.
```




