# Firmwares for the Jafar


Projects: (source for these can be found [here](https://github.com/Kekule-OXC/aladdin-xt-cpld)

**1MB_LPCmod_banks**
    
    Support 1MB SST49LF080A device and split in 2 * 512KB flash banks with the help of a switch connected between the pads marked `1` 
    or shorting the solder pad for permanent selection. Optional device disable feature on long power button press by linking the left
    side of pad `2` to the front panel power button.
    If not interfacing front panel power button, device is always active.
    
**1MB_LPCmod_OSSupport**
    
    Support 1MB SST49LF080A device and gives support to XBlast OS to manage user flash banks. Split in 1 * 512KB and 1 * 256KB user
    banks. Last 256KB bank is reserved for XBlast OS.
    
**1mb_LPCmod_protect**
    
    Support 1MB SST49LF080A device and gives a single 1MB flash bank. Optional switch connected to pad `1` and ground can disable
    writing support. Without any switch, write support is always enabled. Optional device disable feature on long power button 
    press by linking the left side of pad `2` to the front panel power button.
    If not interfacing front panel power button, device is always active.

**256KB_LPCmod_protect**
    
    Support 256KB SST49LF020 and SST49LF020A devices and gives a single 256KB flash bank. Filling the solder pad marked `1` will
    disable writing support. Without any switch, write support is always enabled.
    Optional device disable feature on long power button press by linking the `2` pad to the front panel power button.
    If not interfacing front panel power button, device is always active.



