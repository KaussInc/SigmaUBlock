# SigmaUblock: A Tutorial for a Total Unblock on School-Owned Dell 3120's

This tutorial will guide you through a legal method to create a "total unblock" for school-owned Dell 3120 laptops. It does not modify the laptops themselves, ensuring full compliance with rules. The process requires a few tools and downloads detailed below.

---

## Requirements
- **USB Drive**: Sandisk (64GB to 512GB)
- **External Mouse**: Mandatory for setup
- **Personal Windows Laptop**: To prepare the USB drive

---

## Downloads
Download the following files on your personal laptop:

1. **Tiny10** (Lightweight Windows): [Tiny10 ISO](https://archive.org/download/tiny-10-23-h2/tiny10%20x64%2023h2.iso)
2. **Dell SupportAssist Setup**: [SupportAssistLauncher](https://downloads.dell.com/serviceability/eSupport/SupportAssistLauncher.exe?dl_uid=113770ee-115b-4fa0-aa85-615552a8b845&dc=E206AB2C7485970B241009C6D38AFEED&appname=drivers)
3. **Rufus**: [Rufus 4.5](https://github.com/pbatard/rufus/releases/download/v4.5/rufus-4.5.exe)
4. **Internet Drivers**: [Intel Driver](https://dl.dell.com/FOLDER11737015M/4/Intel-BE200-AX411-AX211-AX210-AX201-AX200-9560-9462-9260_38KK7_WIN_23.60.1.2_A45_01.EXE)
5. **BIOS Update**: [Latitude 3120 BIOS](https://dl.dell.com/FOLDER11967717M/1/Latitude_3120_1.29.0.exe)

---

## Installation

### Prepare the USB Drive
**Warning**: All data on the USB drive will be erased. Back up important files before proceeding.

1. **Run Rufus**:
   - Open File Explorer and navigate to the Rufus executable in the Downloads folder.
   - Launch Rufus.

2. **Configure Rufus**:
   - Under **Device**, select your USB drive.
   - For **Boot Selection**, choose "Disk or ISO image (Please select)" and click **Select** to locate the Tiny10 ISO file.
   - Under **Image Option**, select "Windows To Go."
   - The **Volume Label** thing can be set to whatever, so go wild.  

3. **Start Installation**:
   - Click **Start** and confirm the prompts.
   - Set the local account name to whatever.
   - Let Rufus complete the installation.

4. **Add Files to USB**:
   - Once the installation finishes, throw those files you installed earlier into the usb drive using File Explorer. 
     - SupportAssistLauncher
     - Intel Driver
     - BIOS Update

---

## Booting the USB Drive

### Disable Secure Boot
1. **Access BIOS**:
   - Turn off your school laptop.
   - Plug in the USB drive and turn the laptop on.
   - press **F2** repeatedly to enter the BIOS.

2. **Modify Secure Boot Settings**:
   - Use arrow keys to navigate to **Secure Boot** and press **Enter.**
   - Locate the "Secure Boot Enable" option and uncheck the box.
   - Save changes and exit the BIOS.

### Boot Into USB
1. **Access Bootloader**:
   - Turn on the laptop again, pressing **F12** repeatedly until the bootloader screen appears.

2. **Select USB Drive**:
   - Choose the USB drive option and press **Enter.**
   - Plug in your mouse and follow the on-screen prompts to complete the Windows setup. Use the "Limited Setup" option as internet access won’t be available initially.

---

## Driver Setup

1. **Access USB Files**:
   - Open File Explorer and navigate to "This PC."
   - Locate your USB drive and copy the three files (SupportAssistLauncher, Intel Driver, BIOS Update) to the desktop.

2. **Install Drivers**:
   - Start with the **Intel Driver** and follow the installation prompts.
   - Next, install **SupportAssistLauncher.**
   - If any issues arise, install the **BIOS Update**, restart the laptop, and retry the Intel Driver and SupportAssistLauncher installations.

---

## Important Notes

- **Bootloader Dependency**: To boot into the USB, use the F12 key and select the USB drive every time.
- **USB Safety**: Never unplug the USB while it is running. This could corrupt the drive and require reinstallation.
- **Recommended Browser**: Use OperaGX for its built-in VPN feature.
- **Gaming and Applications**:
  - Avoid large games like COD or Fortnite due to hardware limitations and storage.
  - Lightweight games such as **BTD6, Stardew Valley, Minecraft, Northgard, The Forest, Persona 5, Fallout 3**, and older titles are recommended.
  - Dell 3120 laptops are really good for emulation, so do with that information what you will. 

- **Password Prompts**: If prompted for a password you haven’t set, simply press **Enter.**


