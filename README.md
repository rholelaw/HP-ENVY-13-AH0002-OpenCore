# HP_Envy_13-ah0501na_OpenCore

This repo is a fork of the excellent work by dkoluris over at https://github.com/dkoluris/HP-ENVY-13-AH0002-OpenCore with my fixes for touchscreen and SDreader.

This fork is specifically for the 13-ah0501na model of the HP Envy 13 that was very widely sold in the UK. This model has the dedicated Nvidia MX150 GPU along with the Intel UHD620 iGPU.  Please refer back to dkoluris's repo linked above if your Envy does not have the MX150 or MX250 dedicated GPU as my DSDT.aml and config.plist may not be compatible.

-- 26th July 2020 Update --

Pinned TPD0
Added VoodooSMBUS and VoodooRMI for the Trackpad. (no more jumping around when moving windows etc.)
Removed the PS2TrackPad and PS2Mouse kext entries in the config.plist so VoodooSMBUS and VoodooRMI attach to the RMI Trackpad (F12)
