# logitech-g304-05-clone-research
Some of my initial findings of a cheap (4 dollar USD) logitech G304 / G305 clone. 

## Ways to tell you have a clone
- Will not connect to Logitech G Hub
- DPI Button changes different colors (In order from slowest to fastest: Blue > Yellow > Red > Green)
- In linux, the device ID is 32c2:0066
- The quick start leaflet has an odd font and odd spacing (e.g ©2020Logitech)

## Initial findings

A chip marked BYKC KT8P01 at location U1 on the back side of the board. This turns out to be a KT8P01 2.4Ghz controller IC.

The mouse sensor is a S201B from Instant Microelectronics which supports multiple DPI settings. 

## Overall opinion of the mouse
- Eh. It's...fine. Don't expect quality here, it's similar to most other cheapo mice. Definitely usable in games.

## Special Thanks
- My good friend @RobbieNeko for helping locate the KT8P01 datasheet and freeing it from it's javascript PDF viewer hell <3
