# iamajoe_40

![iamajoe_40](imgur.com image replace me!)

_A short description of the keyboard/project_

-   Keyboard Maintainer: [Joel Santos](https://github.com/Joel Santos)
-   Hardware Supported: _The PCBs, controllers supported_
-   Hardware Availability: _Links to where you can find this hardware_

Make example for this keyboard (after setting up your build environment):

```
qmk compile -kb iamajoe_40 -km default
```

Flashing example for this keyboard:

-   while connecting usb c to computer, click boot
-   send the \*.uf2 file into the drive that appears
-   it should install, flash, restart and all good to go

## Bootloader

Enter the bootloader in 3 ways:

-   **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
-   **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
-   **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
