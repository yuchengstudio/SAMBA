# 1.使用SAM-BA 升级程序
## 利用SAMD21 xplained pro 板了解SAMBA工作流程
https://github.com/yuchengstudio/SAMBA/blob/master/app_note/Implementing%20a%20Bootloader%20on%20SAMD21%20v1.0.pdf

# 2.使用ASFv3 Bootlosers 升级程序
## I2C Slave Bootloader
<br/> Available for SAM D11, SAM D20, SAM D21, SAM L21 and SAM L22
<br/> I2C Master sends the data to be programmed over I2C bus
Documentation:
http://asf.atmel.com/docs/latest/sam0.applications.i2c_slave_bootloader.samr21_xplained_pro/html/appdoc_main.html

## I2C Master Bootloader Bridge example available for SAM D21 device.
<br/> A python script (bootloader.py in script folder) is used on the host PC to send data over USB CDC interface.
<br/> Documentation: http://asf.atmel.com/docs/3.40.0/sam0.applications.i2c_master_bootloader_bridge.samd21_xpro/html/appdoc_main.html




