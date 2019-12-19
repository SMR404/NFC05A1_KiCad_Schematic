# NFC05A1_KiCad_Schematic
Schematic for STMicro's NFC05A1 expansion board converted to KiCad format.

https://www.st.com/en/ecosystems/x-nucleo-nfc05a1.html#resource

The connections of the schematic should be identical to those in the original .SchDoc files provided by STMicro on the NFC05A1 resource page, with some DNM (do not mount) components from the original schematic being omitted.

Appropriate symbols+footprints from the KiCad libraries have been selected for all components except for 1.) the ST253911b (which is the controller IC that comprises the NFC fucntionality) for which a custom symbol is provided and 2.) the planar antenna, for which an incomplete footprint is provided.

Note that the footprint for the planar antenna would need to be modified (read: actually designed), as it was ignored.

No pcb layout is inlcuded since the work on a project that was going to utilize these schematics stopped with the release of STMicro's next NFC IC (the ST25R3916) and the NFC06A1 expansion board.
