# UT99v400-Android-Data-Files
This is a repository of the UT99 v400 Android files from "/android/data/com.ast.ut99/files/UT99" The reason I'm uploading these files is so people can play multiplayer cross platform between windows 98 in a VM called 86box and Android! And cause stupid google is restricting access to the android data files too.

Steps to install UT99 v400 Android data files version:

1. Download all the zip files.
2. Extract them to hard drive in windows 11.
3. Download UT99 v400 from here: https://archive.org/download/ut-99_202512/UT99.iso
4. Install Daemon tools and then double click UT99.iso
5. Open the drive that is UT99 and then double click Setup.exe and install everything except for Directx 7.
6. Wait for the installer to finish and then finally go inside your newly installed UT99 folder and copy all the folders inside it.
7. Paste inside the extracted folder called UT99v400 and DO NOT replace files.
8. Wait for it to finish.
9. You're all set for the next instructions!

How to Setup 86box for Windows 98 in VM:

1. Go here to download 86Box: https://github.com/86Box/86Box/releases/tag/v6.0
2. Download Source code.zip from here for 86Box: https://github.com/86Box/roms/releases
3. Extract 86Box and put it inside a folder under C drive.
4. Extract roms into the folder of 86Box.
5. Rename the roms folder to just "roms"
6. Open 86Box and setup the devices out of the millions of settings it has!!
7. I saved you a step of going through an entire guide and instead just add these devices:

1. Machine type: Miscellaneous (Microsoft Machine Type under miscellaneous)
2. Machine: ASUS TX97 (i430TX)
3. CPU: Intel Pentium 200 MMX
4. RAM: 1024MB
5. Graphics card: S3 ViRGE/DX
6. Graphics accelerator: 3Dfx Voodoo 2
7. Input device: Standard PS/2 mouse
8. Sound card: Sound Blaster 32 PnP
9. Hard disk: 2GB IDE VHD
10. Floppy: 3.5" 1.44MB + 5.25" 360k
11. CD-ROM drives: Two ATAPI 72x

8. Download Windows 98 SE OEM from here: https://archive.org/download/windows-98-second-edition_202407/Windows%2098%20Second%20Edition.iso
9. CD Keys from that archive.org download page: (R667M-TF9CG-MJMTM-WHPWQ-G6XGG) (VY24V-D7M3M-6VGCC-C6667-6Q3G3)
10. Now run the VM and get to bios/setup in the VM.
11. Got to change the boot sequence and change it from C,A to A,C hit esc and then press F10 to save changes.
12. Click Media on the toolbar and then hover over CD-ROM then click on existing and choose Win98.iso
13. Hit Enter when the VM says "Failed to boot Harddrive. Insert system disk and hit enter"
14. Next it should give an image like this:

<img width="720" height="400" alt="17825508413286640347705764515931" src="https://github.com/user-attachments/assets/40431ed9-102b-4d33-bc79-2d241335e021" />

15. Type the number one and hit enter to boot off of the win98.iso from the CD-ROM.
16. Next follow the prompts and choose large disk format and boot off of the CD-ROM again.
17. Keep following prompts to install windows 98 and it will reboot like 3 times during the installation.
18. Every time it reboots you may now choose to boot off of the hard drive instead.
19. Make sure to keep the win98.iso mounted in the CD-ROM during the entire installation process.
20. Congratulations you made it through installing Windows 98 Special Edition OEM!!
21. You may change your machine type to Super Socket 7 instead of that Microsoft machine type under misc.

Steps to get UT99v400 files on the windows 98 hard drive and run it with multiplayer support:

1. Double click the .vhd 2GB file with win98 on it and daemon tools whould mount it
2. Copy the UT99v400 folder to the hard drive you just mounted
3. Next unmount the windows 98 .vhd hard drive and run 86Box
4. Create a shortcut of the exe for UnrealTournament and rename it to whatever you like!
5. Open the game and choose the 3dfx video card if you have installed the 3dfx video drivers otherwise stick with software.
6. Go to multiplayer then click on open location under multiplayer tab.
7. Go to your android tablet or phone and run UT99 native port.
8. Click on multiplayer then start new multiplayer game under multiplayer tab
9. Then go to settings - about device - scroll down to IP Address and type that into open location on the pc running the VM
10. Add the port numbers which by default is :7777
11. Click on start not dedicated on the android tablet.
12. Click on ok button on the open location window on win98 after the map is loaded on the android device.
13. Enjoy!!! 😁

Credit goes to the creators of these programs and game ports!
