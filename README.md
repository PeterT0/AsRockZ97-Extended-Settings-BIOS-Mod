# AsRockZ97-Extended-Settings-BIOS-Mod
A BIOS mod I made for my PC

(Note: This mod works on my AsRock z97 Extreme6 motherboard, it may not work on other editions, however if you do not find any alternatives you may still use this mod with caution if you have either a backup BIOS chip or an EEPROM programer to use as a backup if the mod fails)

I made this mod with UEFItool, the mod contains an extended settings list and Resizable BAR firmware. This mod unlocks Above 4G Decoding, NVMe and many other settings hidden by default. Note that this mod works better on Linux distros (namely Ubuntu) because Windows likes remapping I/O memory without using the Resizable BAR firmware.

First format a USB drive as FAT32, then copy and paste the .z80 file from this repo to the drive. Do NOT rename the file and ensure the file is not zipped.

After creating your flash medium, back up your factory BIOS from the A chip to the B chip. Then plug in your USB drive then select the Instant Flash option in the UEFI. Click enter once the ROM is found and wait for it to finish. Congratulations, you now have access to Above 4G Decoding on your motherboard!

*If any step here goes wrong, flip the BIOS selector switch to B and select the Create Backup option. You may then flip the switch back to A once it says it's done and try again (Only flip the BIOS switch when the system is completely off). If you face more issues feel free to add an issue to this repo.
