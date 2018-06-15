
#                                                               目录
* [1.什么是ISP,什么是IAP](#1-什么是ISP,什么是IAP)
* [1.什么是SAM-BA, SAM-BA的特点](#1-什么是SAM-BA, SAM-BA的特点)

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

# 2. 什么是SAM-BA, SAM-BA的特点
参考第1节内容，SAM-BA应该属于IAP.模型参考如下
![images](https://github.com/yuchengstudio/SAMBA/blob/master/app_note/pictures/SAM-BA_001.jpg)

SAM-BA的特点
```
• Allows the end user to program, verify, and secure a device without a programmer
• Allows the end user to upgrade an application’s firmware
• Provides a configurable Start condition using an I/O pin
• Supports USB-CDC and UART interfaces
• Source code is available, which can be customized to user requirements
```



   



