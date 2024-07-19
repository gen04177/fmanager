# fmanager

This is a simple File Manager developed in C/SDL2, designed to be used on a PS5 with Jailbreak firmware (3.xx-4.xx).

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

Circle - Moving up a directory.

## Next steps:

- Add a virtual keyboard (SDL2) to rename files/directories and create directories with custom names.

## Credits
Credits to J. Tornblom for the SDK and required payloads.
