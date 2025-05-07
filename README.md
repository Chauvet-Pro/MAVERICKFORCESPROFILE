# Maverick Force S Profile

## Software Versions

[V1.250213 - Maverick Force S Profile](https://github.com/Chauvet-Pro/MAVERICKFORCESPROFILE/blob/36fdae0282665d78add39747e6a47c9694de03ea/firmware/V1.250213.zip)
- No new features or performance enhancements were added. This update is for internal use only

[V1.211005 - Maverick Force S Profile](https://github.com/Chauvet-Pro/MAVERICKFORCESPROFILE/blob/8c6825fee733a87f188255bb3bcceca8b306f39d/firmware/V1.211005.zip)
- Fixed issue with gobo fans

[V1.210811 - Maverick Force S Profile](https://github.com/Chauvet-Pro/MAVERICKFORCESPROFILE/blob/8c6825fee733a87f188255bb3bcceca8b306f39d/firmware/V1.210811.zip)
- Added new curve to reduce motor noise

[V1.210317 - Maverick Force S Profile](https://github.com/Chauvet-Pro/MAVERICKFORCESPROFILE/blob/8c6825fee733a87f188255bb3bcceca8b306f39d/firmware/V1.210317.zip)
- Added two additional steps to the CMY macro to add in a full CTO and half CTO preset to that channel in the advanced mode DMX personality

&nbsp;

## USB Software Update Instructions
1. Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message "**USB UPDATE**" will be displayed. Select **<YES>**.  
3.	The next screen will show the software versions available for this fixture on the USB drive.  For multiple versions of the software for the same fixture, use **<UP>** or **<DOWN>** to select the desired version.  Press **<ENTER>**.
4.	The “**USB UPDATE**” screen will re-appear.  Press **<YES>**.
5.	The upgrade will start. **DO NOT** turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: “**USB Update Wait**”. USB update can take several minutes to complete.
   >When the USB firmware is done uploading, in some fixtures the display will change to: “**DO NOT UNPLUG, UPDATING**”.
6.	When the update is completed, the fixture will automatically reboot.
7.	Go to Fixture Information on the product’s menu map and confirm the firmware revision.
8.	When the boot-up process is finished, restart the product.

### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* It is possible to update multiple units with the USB if they are daisy chained via DMX.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the UPLOAD 08 device to fix this.
