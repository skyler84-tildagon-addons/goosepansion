# Goosepansion

*Tildagon Badge Hexpansion by Skyler84*

The **Goosepansion** hexpansion is a capacitive touch addon for the Tildagon badge. Additionally it is designed to be reversible - it can be inserted in either orientation to alter the behaviour of the hexpansion!

## **IMPORTANT**

The hardware of the original Goosepansion had some issues with the active electronics. This is being investigated and a bodge fix will hopefully be released soon!

## Hardware

The goosepansion contains some active electronics that are supposed to allow it to be inserted in either orientation. This is achieved by switching two pairs of pass-fets acting as level shifters and *should* allow the I2C bus to work in either orientation. This had some issues in the original board which is being tested and updated.

### BOM

- 2 * [DMG6602SVTQ-7 complementary PN mosfet pair](https://www.mouser.co.uk/ProductDetail/Diodes-Incorporated/DMG6602SVTQ-7?qs=s5XU71A7K7%252BjMAi7Ml65qw%3D%3D)
- 2 * [DMN63D8LDW-7 dual n-channel mosfet](https://www.mouser.co.uk/ProductDetail/Diodes-Incorporated/DMN63D8LDW-7?qs=wo71MgyKIyE2w30D2buODQ%3D%3D)
- 1 * [M24C64-RDW6TP 8KB I2C EEPROM](https://www.mouser.co.uk/ProductDetail/STMicroelectronics/M24C64-RDW6TP?qs=sGAEpiMZZMutXGli8Ay4kLhq6qGQloYzVbuldgB1vR8%3D)
- 2 * 0603 LED
- 2 * current limiting resistors for LEDs
- 5 * 1k resistors
- 1 * 100k resistor