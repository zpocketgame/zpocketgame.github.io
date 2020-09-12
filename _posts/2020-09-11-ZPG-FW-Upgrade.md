---
title: ZPG Firmware Upgrade Tutorial
published: true
---

This tutorial is for OG ZPG, not ZPG Pro.

1. Download the zip file from [here](https://drive.google.com/file/d/1rWD7lc7W9Sb5Z2ktBUMk17U7Hg1RqEpn)

2. Prepare the micro SD card
	- Unzip the files from the `zpg-Recovery-v1.2.zip`.
	- Move the folders `clockworkmod` and `Overwrite to internal storage` to the root directory of your micro SD card.
	- Insert the micro SD card into your device.

3. Enter the Recovery Mode of the device
	- Switch off your device first.
	- Keep pressing the power button for 3 seconds, then start pressing the Volume UP key a couple of times to make the device boot into recovery mode. 
	- Now you're in the recovery mode main menu. 

4. Install the firmware
	- Select `Backup and Restore`.
	- Select `Restore from/storage/sdcard1`.
	- Select the option starting with `1970-01`.
	- Select `Yes - Restore`.
	- Now the device should start installing the firmware. It will take around 10 minutes or so. It's normal if the screen turns dark. If you want to check if it has been finished or not, press the Volume buttons. **Don't press the power button during this period.** 
	- Once it's finished, return to the main menu by pressing the left arrow button several times. 
	- Select `Reboot System Now`.

5. Overwrite the configuration files
	- Open the ES File Explorer.
	- Navigate to the SD card.
	- Copy all the files under the `Overwrite to internal storage` folder.
	- Navigate to the Internal Storage.
	- Paste all the files to the root directory of the Internal Storage. Choose to overwrite all existing files when the prompt appears. 

6. Finished.