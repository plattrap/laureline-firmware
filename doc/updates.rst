Firmware Updates
****************

Laureline can be updated in the field by way of a MicroSD card.

To perform a firmware upgrade:

#. Download the firmware you wish to install in ``.hex`` format.
#. Format a MicroSD card with a FAT12, FAT16, or FAT32 filesystem. exFAT is not supported.
#. Place the firmware in the root of the MicroSD card and rename it to ``ll.hex``
#. Safely eject the MicroSD card and insert it face-up into the slot on Laureline.
#. Cycle power to Laureline or use the :ref:`save` command to soft-reset the device.
#. Wait for the status LEDs to illuminate. If you are monitoring the command-line interface it will report progress as well.
#. You may now remove the MicroSD card.