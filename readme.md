# pico64

![pico64](https://media.printables.com/media/prints/1177451/rich_content/104bc01f-48fb-41c9-8096-a9813bcdc0d1/thumbs/cover/800x357/png/screenshot-2025-02-04-104829.webp)

Makerunit's 65-key keyboard but using an rp2040 instead of an Arduino pro micro.  
[Printables page](https://www.printables.com/model/1177451-65-key-handwired-keyboard) (Awesome creator, go support them!)

* Keyboard Maintainer: [lividhen](https://github.com/lividhen)
* Hardware Supported: RP2040
* Hardware Availability: [Raspberry Pi](https://www.raspberrypi.com/products/raspberry-pi-pico/)

Make example for this keyboard (after setting up your build environment):

    make pico64:default

Flashing example for this keyboard:

    make pico64:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
