# fmanager

This is a simple File Manager developed in C/SDL2, designed to be used on a jailbroken PS5 (1.xx-4.xx).

## Prerequisites
- elfldr.elf
- shsrv.elf
- ftpsrv.elf

## How to Use
1. Send the elfldr.elf payload to port 9020.
2. Send the shsrv.elf payload to port 9021.
3. Send the ftpsrv.elf payload to port 9021.
4. Copy the fmanager.elf to `/data` directory on your PS5.
5. Execute `telnet [PS5-IP] 2323`.
6. cd `/data`.
6. Run the command `hbldr fmanager.elf`.

## Controls

Triangle - Delete files/directories.

R - Copy.

L - Paste.

Cross - Enter the selected directory.

Circle - Moving up a directory/Close the virtual keyboard.

Square - Create a new directory/Backspace.

Touchpad - Rename files and directories.


## Credits
- J. Tornblom - SDK and required payloads.
