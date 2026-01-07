# Install Guide:
## Download [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg) and Python
# Windows MacOS recovery install:
Navigate to the "Utilities" folder, then open the "macrecovery" folder, and type cmd in the address bar, and paste this exact command in the command line "py macrecovery.py -b Mac-FFE5EF870D7BA81A -m 00000000000000000 download"
# Linux MacOS recovery install:
Use the CD command
## cd ~/Downloads/OpenCore-0/Utilities/macrecovery/" (change the command to match your macrecovery folder
and run this command: "python3 ./macrecovery.py -b Mac-E43C1C25D4880AD6 -m 00000000000000000 download".

# Both Operating Systems (Final Step)
Move both the EFI folder and the "com.apple.recovery.boot" to a flash drive formatted to FAT32 with the GPT file-system. Boot into the USB, run the installer. In the installer open disk utility and format the drive you wish to install macOS on to the APFS format. Run the installer. In the macOS operating system, download OCAuxilaryTools/OCAT and mount the ESP. Move the EFI folder you used there and enjoy!

What works:
Pretty much everything you need and some Apple ecosystem features aswell.

What doesn't
Built-in speaker (aux/bluetooth headphones/speakers work).
