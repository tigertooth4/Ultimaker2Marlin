# Single/Dual Extrusion Ultimaker2Marlin Firmware

This is a modification to the original marlin firmware for Ultimaker2, which can be used for both single and dual extrusions. Changing extrusion modes has been implemented as easy as possible. No need to upload firmware while changing extrusion modes.

## Main features
- Base on the Marlin firmware for Ultimaker 2;
- Keep the original firmware intact;
- Menu change the extrusion mode, reboot machine to apply;
- A new dual extrusion printhead is supported;
- Human aided bed levelling and z-offsets calibrations;
- Offsets stored in EEPROM;
- Menu items to change the offsets values;


## Use
- Enable the *ALTER_EXTRUSION_MODE_ON_THE_FLY* parameter in Configuration.h file and other parameters related to take effect.

