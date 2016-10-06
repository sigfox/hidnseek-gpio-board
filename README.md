<p align="center"><img src ="http://www.sigfox.com/themes/custom/sigfox/images/logo-2016.svg" width="300"></p>

## SIGFOX GPIO Extension Board for the HidnSeek

This repo contains the .brd and .sch files required for the HidnSeek GPIO Extension Board. The design utilises a PCF8574N to breakout the I2C pins and allow for 8 additional digital I/O pins. The board also contains a reset button to place the device into DFU mode for re-flashing.

The intention of this board is to allow developers and makers to utilise the underlying hardware and to expand it with their own designs.

This board should be used in conjunction with the SIGFOX HidnSeek Dev Libraries as the I2C GPIO is driven by the wire.h library with a specific memory address (0x20). 

<p align="center"><img src ="https://raw.githubusercontent.com/sigfox/hidnseek-gpio-board/master/Images/hidnseek-gpio.png" width="500"></p>

See https://github.com/hidnseek/hidnseek for more info about the HidnSeek.

Credit to **Stephane Driussi** for the daughter board pin layout
