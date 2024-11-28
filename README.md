# Sigma Ublock
SigmaUblock is a terrible name i came up with for a tutorial on a total unblock for school-owned Dell 3120's. This "exploit" has no affect on the laptops themselves, so it's completely legal. 
## Requirements
You'll need a 64-512 Sandisk USB Drive, an external mouse (yes it's required), and a personal Windows laptop. 
## Downloads
Download all of these on your personal laptop, I'll tell you how to use them later

Tiny 10 https://archive.org/download/tiny-10-23-h2/tiny10%20x64%2023h2.iso 

Setup https://downloads.dell.com/serviceability/eSupport/SupportAssistLauncher.exe?dl_uid=113770ee-115b-4fa0-aa85-615552a8b845&dc=E206AB2C7485970B241009C6D38AFEED&appname=drivers 

Rufus https://github.com/pbatard/rufus/releases/download/v4.5/rufus-4.5.exe  

Internet https://dl.dell.com/FOLDER11737015M/4/Intel-BE200-AX411-AX211-AX210-AX201-AX200-9560-9462-9260_38KK7_WIN_23.60.1.2_A45_01.EXE 

Bios https://dl.dell.com/FOLDER11967717M/1/Latitude_3120_1.29.0.exe
## Installation
Keep in mind during this installation, everything on your USB Drive is going to get deleted, so i recommend backing up any important files. Go to File Explorer - Downloads - Rufus, then run rufus.  in rufus, under device, make sure your USB Drive is selected. then under boot selection, select "Disk or ISO image (Please Select)" then on the right press select, and choose the tiny10 ISO file in downloads. Then, under "Image Option", make sure to choose "Windows To Go". you can change the volume label to whatever you want, then press start. In the dialogue that shows up, select all the options and change your local account name if you'd like. Then press okay, then okay, and let it install. Once Rufus gets finished, throw the setup, internet, and bios files you downloaded into the root of your USB Drive. 


    
## Booting
Now plug in the USB Drive into your school laptop which should be off. Then turn it on, and after start spamming the F2 button till a scary screen shows up. You have to use arrow keys for this part. Scroll down til you see secure boot, press enter on that, then in the sub-section there should be a part that says "secure boot enable", you need to go to that, then deselect the box, selecting it with tab then turning it off with enter. now, save and exit. Turn the computer on and do what we did before, but instead use the F12 key, where a less scarier screen should pop up, which is your boot-loader (how you'll get into this installation ). You'll select the option that will say something like usb drive or something of the sort, then press enter. you'll want to plug in your mouse for this. now, go through the Windows setup. You won't have internet for the time being so just proceed with limited setup. 
## Driver Setup
Open File Explorer from the search bar, go "This PC", click the thing shaped like a usb drive, and for this part im not 100% on what to do. But you first need to take those 3 files and drag then to your desktop. Try installing the Intel driver. If that works, do the one that says supportassistlauncher. If that doesn't work, do BIOS, restart, then do the Intel Driver, then do supportassistlauncher. And now you're done. 
## Things You Should Know
Anytime you want to boot into the USB, you have to use the bootloader. Never pull out the USB while it's loaded, it will most likely corrupt the USB, meaning you have to do all of this again. Use OperaGX as a browser, as it has a built in VPN. Most big games aren't gonna run, like cod or fortnite, so i wouldn't recommend taking up all of your drives space with it. Games like BTD6, Stardew Valley, Minecraft, NorthGuard, The Forest, Persona 5, Fallout 3, and older 3d games or smaller games will probably run well.The 3120 is also really good with emulation, so do with that information what you want. If you ever get prompted to add a password, in which you never had one, just press enter. Anytime you restart, you'll boot into your school partition, so anytime you want to boot into the usb, you have to go to it with f12. That's pretty much it. 
