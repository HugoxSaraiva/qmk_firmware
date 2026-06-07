# How to

Flash each side:
qmk flash -kb sofle/rev1 -km hugoxsaraiva -bl uf2-split-left

qmk flash -kb sofle/rev1 -km hugoxsaraiva -bl uf2-split-right

To enter device in Bootloader mode, start the controller while pressing the upper left (on left side) and upper right (on right side) key. You can also double tap the reset button next to the TRRS port.
The flash should copy the file directly to the device.
