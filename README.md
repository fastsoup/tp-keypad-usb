# tp-keypad-usb
Documenting the journey of adapting a Lenovo ThinkPad T410/X220 keyboard to interface via USB. Not a tutorial but more of a log of steps taken.

I love the 7 row ThinkPad keyboards and wanted to see if I could convert one to an ultra-slim/portable USB keyboard. This is just a part of a crazy dream project to one day see a hobbyist DIY laptop, something that may be within reach thanks to the Framework mainboard. The following video was an inspiration to take the jump and tackle the keyboard aspect: [Triple-Screen Laptop DONE RIGHT!](https://www.youtube.com/watch?v=aUKpY0o5tMo)

## Goals:
- Produce an ultra-thin keyboard that can be external USB or untilized in conjuction with something like the Framework Laptop mainboard
- Minimize PCB design as possible to lower barrier to entry
- Utilize Raspberry Pico Pi or RP2040 based substitute 
- USB C / solderable interface
- Functional Trackpoint

## Sources and Research:
  - https://github.com/rampadc/arduino-thinkpadkb-usb
  - https://github.com/thedalles77/USB_Laptop_Keyboard_Controller
  - https://www.youtube.com/watch?v=8nqvHDSDzKk
    - A very similar implementation, proof this idea can work.
  - https://drive.google.com/file/d/0B6IqcVTk0jpYZ18yenc1b2d0QkE/view?resourcekey=0-nYqUiMwWlOcGj5tjHnmOEA
    - Schematics for X220

## The Build Log

Lenovo ThinkPad T410/X220 replacement keyboard
![](https://m.media-amazon.com/images/W/IMAGERENDERING_521856-T2/images/I/61oJ1zRdV2L._AC_SL1500_.jpg)
