# Disadv68

![disadv68](https://i.imgur.com/kJbvQvUh.jpeg)

*Sawed kinesis advantage keyboard (influenced by dactyl-cc)*

* Keyboard Maintainer: [Janez Kranjski](https://github.com/tree-in-forest)
* Hardware Supported: *WeAct Studio STM32F411CEU6 3.1*, [everything else](https://github.com/tree-in-forest/disadv68)
* Hardware Availability: *[STM32F411CEU6](https://github.com/WeActStudio/WeActStudio.MiniSTM32F4x1#legitimate-purchase-links-as-well-as-pirated-links)*

Make example for this keyboard (after setting up your build environment):

    make handwired/disadv68:default

Flashing example for this keyboard:

    make handwired/disadv68:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix and plug in the keyboard
* **Physical reset button**:
  * Method 1: When the power is on, press the `BOOT0` key and the reset key, then release the reset key, and release the `BOOT0` key after 0.5 seconds
  * Method 2: When the power is off, hold down the `BOOT0` key, and release the `BOOT0` at 0.5s after the power is on
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
