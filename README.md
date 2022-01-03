# EUROtronic Spirit
This repo is just for me to write down all the things I learn about the Spirit. I try to get as much info here as possible.

## Images
![EUROtronic Spirit](/images/spirit_001.jpg)
![EUROtronic Spirit without top cover](/images/spirit_002.jpg)
![EUROtronic Spirit zwave board front](/images/spirit_003.jpg)
![EUROtronic Spirit zwave board back](/images/spirit_004.jpg)
![EUROtronic Spirit temp control board with motor](/images/spirit_005.jpg)
![EUROtronic Spirit temp control board with atmel processor](/images/spirit_006.jpg)

## Composition
The Spirit consists of two boards. The first Board contains an ATMEL [ATmega329PA](https://www.microchip.com/en-us/product/ATMEGA329PA#) ([datasheet](/docs/Atmel-8284-8-bit-AVR-microcontroller-ATmega169A_PA_329A_PA_3290A_PA_649A_P_6490A_P_datasheet.pdf)). This board is also connected to the motor. I call this board the temp control board.

The second board contains an Silicon Labs [ZM5202](https://www.silabs.com/wireless/z-wave/500-series-modules/device.zm5202) ([datasheet](/docs/DSH12435-15.pdf)) module with a Silicon Labs SD3502 ([datasheet](/docs/DSH12206-13.pdf)) chip.