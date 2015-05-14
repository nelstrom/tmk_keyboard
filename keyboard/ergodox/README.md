# How to flash the ergodox keyboard

The `flash` script is provided as a convenience. To run it:

    cd keyboard/ergodox
    ./flash

You will be prompted to press the Teensy reset button. This is a physical button on the ErgoDox, situated on the Teensy chip. You'll need a long sharp object such as a pencil to reach through the hole and press the button.

Alternatively, you can use the 'software reset' function key. In my layout, this is a key on the right hand, at the top left of the finger pad, on layer 1.

# How to modify the keyboard layout

Open up the `keymap_nelstrom.h` file and make changes. To apply the changes, save the file and run the `flash` script.

Refer to the [`doc/keycode.txt`][codes] file for definitions of the keycodes.

[codes]: https://github.com/tmk/tmk_keyboard/blob/master/doc/keycode.txt
