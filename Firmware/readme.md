# media_pad

![media_pad](https://imgur.com/a/ofdoh0z)

I am making a macropad under Hack Club. My goal with this macropad is to allow for dedicated macros for streaming and editing alonside a screen that states which OBS I am on.

* Keyboard Maintainer: [Guillermo Manalang III](https://github.com/koyasan)
* Hardware Supported: Seeed XIAO RP2040, 1x 0.91 inch OLED display
* Hardware Availability: [(https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html)]

Make example for this keyboard (after setting up your build environment):

    make media_pad:default

Flashing example for this keyboard:

    make media_pad:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
