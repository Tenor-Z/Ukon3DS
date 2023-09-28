# Ukon3DS
 A trojan/bricker program for the Nintendo 3DS family

# Proof of Concept
 By writing invalid data to various parts of the system's NAND (SYSNAND) and removing particular components required
 for the console to boot, we can evidently brick the console from powering on (there is no system menu to boot to since
 it gets wiped).

# How to build
Download and extract the .zip folder. Run a CLI in the directory and use the 'make' command. Output should be a .elf, .smdh and .3dsx file.
You can run the 3dsx file in The Homebrew Launcher or similar launchers to run the program
