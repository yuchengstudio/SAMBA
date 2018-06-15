
#                                                               目录
* [1.什么是ISP,什么是IAP](#1-什么是ISP,什么是IAP)
# 1. 什么是ISP,什么是IAP
```
    In-System Programming (ISP) is programming the microcontroller while the chip is on 
board and connected to many other components.During ISP every pin on microcontroller 
is disabled and chip is programmed by means of a programmer which follows some protocol.
Chip removal is not necessary during programming.

    General board manufacturer , solder and fit the chip before programming the chip and 
not vice versa. ISP comes handy during this time.

    There is another kind of programming known as In Application Programming(IAP) which 
is more flexible than ISP . A required programmer is not necessary and existing UART ,
USB peripherals on the microcontroller will enable writing the program to flash memory.
A bootloader software resides in The microcontroller which will down the rest of the 
firmware via (UART /USB). Many hobby development boards in microcontroller market works 
this way.
```

