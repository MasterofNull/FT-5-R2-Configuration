# FT-5 Firmware Update and PrusaSlicer Integration 

## Marlin 2.1.1 Config Files:
Use the Configuration.h and Configuration_adv.h to replace the similar files for the Marlin 2.1.1 build.
Or use the firmware.hex file and use Prusa or other software to update FT-5 firmware.

Note: I did not have any luck building Marlin 2.1.1 firmware from Arduino IDE. Use PlatformIO instead. 

## Prusa Device Presets:
Use the PrusaReseach.ini to replace the same named file at location below.
Then use the Prusa Configuration Wizard to add the printer and filament presets you want. 
(Should be the first option/machine in the wizard.)

Windows:    C:\users\<username>\AppData\Roaming\PrusaSlicer\vendor

MacOS:      /Users/<username>/Library/Application Support/PrusaSlicer/vendor

Linux:      ~/.PrusaSlicer/vendor
