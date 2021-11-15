# Macropad 12plus1
I wanted to have a macropad for some time now. I actually plan on building a custom mechanical keyboard, but I thought let's start small. So a macropad.

## Where does this design come from?

I did not come up with this fully by myself. I watched some youtube videos about different macropads and also checked out Reddit. 
In the end I came across a [design from Ryan Bates](http://www.retrobuiltgames.com/the-build-page/macro-keyboard-v2-0/) from retrobuiltgames.com which I liked. 
So the credit for the layout goes to him. However, as I am based in Europe ordering from Tindie makes little sense, as the shipping is three times the price of the board and I also did not want to wait. Also I saw a lot of handwired keyboard builds, so I set out to do this myself.

## How did you do it?

I recreated the layout in [keyboard-layout-editor.com](http://www.keyboard-layout-editor.com/) and imported the raw data to [ai03 Plate Generator](https://kbplate.ai03.com/). 
This will allow you to create a DXF file, which I then again opened in [FreeCAD](https://www.freecadweb.org/) to create the plate of the pad. From there I then created the shell (basically the majority of the body) and the bottom part, that also has some standoffs for the Pro Micro controller board.

I am writing this down as if it is an easy afternoon adventure, but in fact it took me quite some time and trial and error in FreeCAD to get to the result that you can find here.

## Firmware

The firmware this runs on is [QMK](https://qmk.fm/), again differing from the original from Ryan Bates, which uses Arduino code. The keymap is very basic so far and rather a template to build your own than a ready to use one.
You can find my version of the firmware here: https://github.com/Sono-Gomorrha/qmk_firmware/tree/master/keyboards/handwired/12plus1 
It is not yet in QMK, once it is I will update here.
