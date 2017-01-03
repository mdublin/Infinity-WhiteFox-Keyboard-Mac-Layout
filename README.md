This layout is intended to work with Infinity WhiteFox 65% keyboard for Mac. 

Step 1. Make sure you have ```dfu-util```, a USB CLI utility, installed : ```$ brew install dfu-util``` (this also requires Xcode, so make sure you have Xcode installed as well).

Step 2. Flash the firmware of the keyboard by inserting a paperclip into the hole in the underside of the keyboard (a little orange light will go on and the LEDs on the keyboard should turn off)

Step 3. After you download this repository, CD into it and run the following command ```$ dfu-util -D kiibohd.dfu.bin```
The exiting message of the dfu process should be something like ```state(7) = dfuMANIFEST, status(0) = No error condition is present dfu-util: unable to read DFU status after completion```

You should be good to go, here's the actual layout (ignore where the vertical enter key is on the left hand side, if you have a Infinity WhiteFox 65% you may have a different key there, but the layout should be identical as far as the USB codes go):

![layout screen shot](https://github.com/mdublin/Infinity-WhiteFox-Keyboard-Mac-Layout/blob/master/WhiteFox%20Layout%20for%20Mac.png?raw=true)



