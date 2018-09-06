hid-multitouch
==============

Overwrite of hid-multitouch driver for kernel v4.18.5.

Run:

    $> make
    $> sudo make install
    
_______________________________________
This driver improve error in dmesg log "incomplete report 16/2^16-1",
improve disconnect (beta test),
improve load processor by irq requests.

Driver writted by Benjamin Tissoires.
For compile needed comment:
//hdev->quirks |= HID_QUIRK_NO_EMPTY_INPUT;
and src will be compile normally.
