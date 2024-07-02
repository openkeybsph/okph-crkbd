# OKPH keymap for the CRKBD
This keymap is costumized
## Layers
- 1 - Default layer
- 2 - Aim to be a usable layer for GUI centric app use
- 3 - Has the F keys and cursor mobility related commands
- 4 - Has num keys and other missed keys in default layer
- 5 - LED Control Layer and change base layer to 2.

Note: The keymap can be easily changed via 'usevia.app' in a chromium based web browser

## Custom OLED (USB-C on Left)
- Left side:
    - Layer indicator
    - Keyboard pet Luna from @HellSingCoder <https://github.com/HellSingCoder/qmk_firmware/tree/master/keyboards/sofle/keymaps/helltm>
- Right side
    - Openkeybs PH pixel art logo
    - WPM counter

## Troubleshooting
- Having trouble flashing?
	* Flash the clear EEPROM by flashing the clear EEPROM example of arduino then retry

## Encountered Some Bugs?
- Feel free to submit an issue in this git

## Building
- This step assumes that you already have qmk msys in your pc (https://docs.qmk.fm/newbs_getting_started)
1. Copy this directory to `your_qmk_directory/keyboards/crkbd/keymaps/`
2. run `qmk flash -kb crkbd -km okph-crkbd`
3. Wait for compilation to complete
4. Once `reset your controller now` message appears, briefly short the two reset holes with wire
5. Wait for flash to finish