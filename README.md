# Macro-Pad-Raspberry-Pi-Pico-
This is a custom, 16-key, macro pad made using the raspberry pi pico and the pico rgb keypad by pimoroni. I have also utilized another github project called rgbkeypad which is very helpful!


KEY FEATURES:
-on keypress a function and color is run based on keybindings which I have set up.
-LEDs timeout and turn off after 1 minute of no keypresses. All the keys still work, just the LEDs turn off so the board doesn't get too hot.
-all written in CircuitPython
-plug and play. code.py will run right when the board is plugged into a PC.


LIMITATIONS:
-I wanted to set this up with the Python os library, but all MicroPython and CircuitPython implimentations do not have the methods to monitor programs opened on the pc.
-I also wanted to use MicroPython but there is no USB_HID support for this board at least. Hopefully this changes in the future.


FUTURE IDEAS:
-maybe change it so the running lights (no keypresses) are dimmer and colored to their specific program.
-paint on the keycaps so it looks a little nicer.