# goomsë-cat

code is based on https://github.com/puckipedia/efi-example.

have you ever wanted a moving goomsë cat as your bootloader? of course!

now you can.

![image]()

to exit the bootloader, enter the konami code.

## installing

`make` will generate the file `gooseload.efi`.
Make that your default bootloader, and the wonders of goomsë cat will appear the next time you boot up.

Alternatively, you can also just try it in a virtual machine (qemu) by running `make go` to open up qemu.

If you do go the virtual machine route, you will need the proper firmware - Open Virtual Machine Firmware (OVMF).

Check out http://www.tianocore.org/ovmf/ for more info and (https://sourceforge.net/projects/edk2/files/OVMF/ or https://github.com/BlankOn/ovmf-blobs) to download.

