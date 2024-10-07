# Sigma Ublock
This is made by a skid, for skids, who want to completely unblock their school-owned dell latitude 3120s. This "exploit" has no affect on the laptops themselves, so it's completely legal. 
## Requirements
You'll need a 64-512 Sandisk USB Drive, and an external mouse (yes it's required) and a personal Windows laptop. 
## Downloads
Download all of these, ill tell you how to use them later
Tiny 10 https://archive.org/download/tiny-10-23-h2/tiny10%20x64%2023h2.iso 
Setup https://downloads.dell.com/serviceability/eSupport/SupportAssistLauncher.exe?dl_uid=113770ee-115b-4fa0-aa85-615552a8b845&dc=E206AB2C7485970B241009C6D38AFEED&appname=drivers 
Rufus https://github.com/pbatard/rufus/releases/download/v4.5/rufus-4.5.exe  
Internet https://dl.dell.com/FOLDER11737015M/4/Intel-BE200-AX411-AX211-AX210-AX201-AX200-9560-9462-9260_38KK7_WIN_23.60.1.2_A45_01.EXE 
Bios https://dl.dell.com/FOLDER11967717M/1/Latitude_3120_1.29.0.exe
## Installation
Plug your USB Drive in, then go into file explorer, downloads, and run rufus. Warning, EVERYTHING ON YOUR USB DRIVE WILL GET DELETED. in rufus, under device, make sure your usb drive is selected. then under boot selection, select "Disk or ISO image (Please Select) then on the right press select, and choose the tiny10 file. then under image option, make sure to choose "Windows To Go". you can change the volume label to whatever you want, then press start. in the dialogue that showed up, select all the options and change your local account name if you'd like. Then press okay, then okay, and let it install. Once Rufus gets finished, throw the setup, internet, and bios files you downloaded into the root of your USB Drive. 


    
## Booting
Now plug in the USB Drive into your school laptop which should be off. now you gotta turn it on, then spam the f2 button till a scary screen button pops up. You have to use arrow keys for this part. Scroll down til you see secure boot, press enter on that, then in the sub-section there should be a part that says "secure boot enable", you need to go to that, then deselect the box, selecting it with tab then turning it off with enter. now, save and exit. this time we are gonna turn the laptop on while spamming f12, where a less scarier screen should pop up, which is your boot-loader (how you'll get into this installation ). you'll select the option that will say something like usb drive or something of the sort, then press enter. you'll want to plug in your mouse for this. now, go through the Windows setup. You won't have internet for the time being so just proceed with limited setup. 
## Driver Setup
Open File Explorer from the search bar, go "This PC", click the thing shaped like a usb drive, and for this part im not 100% on what to do. But you first need to take those 3 files and drag then to your desktop. Try installing the Intel driver. If that works, do the one that says supportassistlauncher. If that doesn't work, do BIOS, restart, then do the Intel Driver, then do supportassistlauncher. And now you're done. 
## Things You Should Know
Anytime you want to boot into the USB, you have to use the bootloader. Never pull out the USB while it's loaded, it will most likely corrupt the USB, meaning you have to do all of this again. Use OperaGX as a browser, as it has a built in VPN. Most big games aren't gonna run, like cod or fortnite, so i wouldn't recommend taking up all of your drives space with it. Games like BTD6, Stardew Valley, Minecraft, NorthGuard, The Forest, Persona 5, Fallout 3, and older 3d games or small games. That laptop is also really good with emulation, so do with that information what you want. If you ever get prompted to add a password, in which you never had one, just press enter. After a restart, you'll boot into your schools partition. 
