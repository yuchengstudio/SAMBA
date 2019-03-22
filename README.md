# 1.使用SAM-BA 升级程序
## 利用SAMD21 xplained pro 板了解SAMBA工作流程
https://github.com/yuchengstudio/SAMBA/blob/master/app_note/Implementing%20a%20Bootloader%20on%20SAMD21%20v1.0.pdf

# 2.使用ASFv3 Bootlosers 升级程序
## 2.1  I2C Slave Bootloader
<br/> Available for SAM D11, SAM D20, SAM D21, SAM L21 and SAM L22
<br/> I2C Master sends the data to be programmed over I2C bus
<br/>Documentation:
http://asf.atmel.com/docs/latest/sam0.applications.i2c_slave_bootloader.samr21_xplained_pro/html/appdoc_main.html

## I2C Master Bootloader Bridge example available for SAM D21 device.
<br/> A python script (bootloader.py in script folder) is used on the host PC to send data over USB CDC interface.
<br/> Documentation: http://asf.atmel.com/docs/3.40.0/sam0.applications.i2c_master_bootloader_bridge.samd21_xpro/html/appdoc_main.html


## 2.2 SAM D21 USB MSC Bootloader
<br/>It can detect a mass storage device (for example a USB thumb-drive) when connected to the USB-port. 
<br/>If this device contains an updated firmware image, the bootloader can update the flash of the device with new firmware.
<br/>Documentation: http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-42352-SAM-D21-XPRO-USB-Host-MSC-Bootloader_Training-Manual_AN8185.pdf

## 2.3 SPI SD Card Bootloader (SPI Master bootloader)
<br/> Available only for SAM D20
<br/> Programming through SPI Master Bootloader
<br/> SD/MMC card is used as the SPI slave to store the binary file to be programmed to the device.
<br/> The user needs to update the SD card with image to be flashed
<br/> Documentation:
 http://asf.atmel.com/docs/latest/sam0.applications.spi_master_bootloader.samd20_xplained_pro/html/appdoc_main.html
 http://ww1.microchip.com/downloads/en/AppNotes/Atmel-42455-SAMD20-SD-Card-Bootloader_Application-Note_AT06037.pdf
 
 
 # 3.其他的bootloader方法：
<br/>Available for UART and I2C interfaces
<br/>Bare-metal code
<br/>Easy to modify for customer requirements
<br/>Available for devices SAM D10, SAM D20, SAM D21, SAM C21, SAM L10, SAM L11, SAM E54
https://microchiptechnology-my.sharepoint.com/:u:/r/personal/alan_yu_microchip_com/Documents/Attachments/Alan_Studio/daily%20work/application%20solution/32bit%20MCU+MPU/SAM%20Bootloader%20-%20reference_code.zip?csf=1&e=tAFr1k

 

