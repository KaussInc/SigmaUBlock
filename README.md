This is a tutorial for "unblocking" school owned Dell Latitude 3120's. if you have a different type of dell windows laptop, when you install the drivers, use the driver version for that type of laptop. This doesn't affect your school laptop in any way, but proceed with caution, as you can get in big trouble for stuff like this. You'll need a 64GB-512 USB drive. Use a Sandisk one. 


There's 2 routes. Tiny10, and Windows10. Tiny10 does NOT come preinstalled with drivers at all, and driver installs on school computers is really freakilicious, so i cant recommend it. You'll have to do the driver installation all on your own with Tiny10. So, we're doing base Windows10. 


I'm probably gonna make a video tutorial on this, because i don't like typing up a storm. But let's start.


Windows10 Creation tool - https://go.microsoft.com/fwlink/?LinkId=2265055 go through the installation process and download the iso file. 


While that installs, install this https://downloads.dell.com/serviceability/eSupport/SupportAssistLauncher.exe?dl_uid=113770ee-115b-4fa0-aa85-615552a8b845&dc=E206AB2C7485970B241009C6D38AFEED&appname=drivers


And while both of those install, install this file too https://github.com/pbatard/rufus/releases/download/v4.5/rufus-4.5.exe


After all of those finish installing, plug in your usb into your laptop. run rufus, select the usb your using, and note, EVERYTHING ON YOUR USB WILL GET DELETED. just letting yk. now on boot selection, switch to disk or iso image, and select your new windows iso file. change the volume label if you so desire, change the image option from Standard Windows Installation to Windows To Go, click start, select all 4 options and change your name if you want, then click okay and accept the thing that comes after. 


when that finishes, open file exploreer, where gonna grab that support file, and throw that on the root of our brand new Windows To Go USB Drive.

Go to your school computer, plug the usb in, turn on the computer and spam f2. we need to turn off secure boot. 
