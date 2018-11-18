hid-multitouch
==============

Overwrite of hid-multitouch driver for kernel v4.19.2

Run:

    make
make install # (which will just copy the .ko file to the `/lib/modules/...
```

Use target `reload` to uninstall current module and install a new one.
    
_______________________________________
This driver improve error in dmesg log "incomplete report 16/2^16-1",
improve disconnect (beta test),
improve load processor by irq requests.
