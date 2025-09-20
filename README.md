# SunmiOS-3.5.0-V2-DEBLOATED
Debloating project of sunmi os 3.5.0 for sunmi devices model v2 based on dafish7 repo that you can find here: <a href="https://github.com/dafish7/Sunmi-v2-Firmware-">dafish7</a>
Thanks <3 

## BACKUP ##
BEFORE USING THIS GUIDE BE SURE TO MAKE A FULL BACKUP USING MTKCLIENT.


## INSTALLATION AND REQUISITES ##

Requisite 1: MTKCLIENT
1. Download <a href="https://github.com/bkerler/mtkclient">MtkClient</a>
2. Unzip it in a folder easily accessible for you.
3. Open CMD in the same directory.
4. Follow the official <a href="https://github.com/bkerler/mtkclient?tab=readme-ov-file#windows">Installation guide</a>

Requisite 2:
1. Download my official MtkClient ROM dump from here: <a href="https://drive.google.com/file/d/16cGU3oo7NQuf6vfAlmDAA-P6Y3Y7-Vnd/view?usp=sharing">download rom</a>
2. Unzip it in the same folder where mtkclient is, it must be something like this:
  - Main folder <br>
   -- /mtkclient/ <br>
   -- /3.5.0/ <br>


## FLASHING THE ROM ##    
   
1. Power off your device if it's not already. <br>
1a. If it's stuck in the flower boot logo, hold the power button for 10 seconds to force shutdown. <br> 
2. Open mtkclient-gui.bat and let mtkclient to power up the GUI. <br>
3. While device is completely powered off connect the usb cable while holding volume down. <br>
4. MtkClient will automatically detect the device and will bring you to the main flash menu. <br>
  4a. Before doing anything else from here backup your current rom form the "Read partition tab". <br>
  4b. Check all partitions and click "Read". Select a folder and wait for the backup to finish. <br>
5. Select the "Write partition" button. <br>
6. Click on select from directory and select the previous downloaded "3.5.0" folder. <br>
7. Check if every file is being actually detected and if so, click on the "Write" button. <br>
8. Wait for the flashing to complete. <br>
9. After the flashing is complete, you will notice the "Done" text where the progessing bar was. <br>
9a. If so, disconnect the usb cable and power on your device. <br>
10. Enjoy.

## DEBLOATING THE ROM ##
You will already have the debolated rom from all the original SUNMI OS apps even the main ones that take cares of SN activation... (if you know what i mean) ((proinfo.bin -- hex editor 😏​)).


BUT.
I do already included magisk manager v29 with a patched boot image so you can do whatever you want with it and install whatever you need. 
I do excluded anything related to Google Play 'cause it will make the rom so slow but i do already installed for you some apps:

- Aurora Store
- Simple Pixel Launcher FOSS (yeah the sunmi one was soooo bad)
- FOSS Material File Manager with root explorer enabled
- Via Browser (it's so good and so lightweight damn)

## PROBLEMS? ##
If anything goes wrong feel free the join dafish's discord server to discuss everything related: <a href="https://discord.gg/jHpeHhRWez">Join us on Discord</a>
