[![endorse](http://api.coderwall.com/sebseb7/endorsecount.png)](http://coderwall.com/sebseb7)


pentarm13uxx
============

A small template project (blinking led) for the new lpc1347 (successor of the popular lpc1343).

Including Makefile, linker-script and cmsis and microcontroler header files.

Also includes eagle files for a small breaboardable eval-board.


- - -

####lpc1347 features


* 12k sram (was 8k)
* 64k flash (was 32k)
* 4k EEPROM (new)
* 72Mhz
* USART,I2C,2xSPI
* 12Bit ADC (new)
* USB_MSC, USB_HID, USB_CDC and USB_DFU in rom (new)
* usb-bootloader in rom

- - -

price of the eval board: ~$15

- - -

####BOM:

* C1,C2 : 22pF 0402
* C3,C4 : 100nF 0402
* C6,C8 : 10nF 0402
* C5,C7 : 1µF 0805
* R2,R3,R6,R7 : 150R 0402
* R4,R5 : 33R 0402
* R1,R8,R9 : 15k 0402
* R10 : 1k5 0402
* T1 : Si3102DS SOT23 (or other pfet)
* Q1 : 12Mhz MT (farnell: 1842056)
* IC1 : lpc1347 QFP48 (farnell: 2103477)
* IC2 : LT1763CS8-3.3 SOIC8 (farnell: 1273617)
* X1 : Mini USB Connector SMD (farnell: 1125348)
* X2,X3 : Pin-Header 10 Pin
* X4 : Pin Header 2 Pin
* X5 : Pin Header 4 Pin
* LED1 : RGB LED PLCC4 common annode
* SW1,SW2,RST : MCTAEF-25N (farnell:1605484)

- - -

data sheet  : http://www.nxp.com/documents/data_sheet/LPC1315_16_17_45_46_47.pdf

user manual : http://www.nxp.com/documents/user_manual/UM10524.pdf

toolchain   : https://launchpad.net/gcc-arm-embedded

- - -   
![brd](https://raw.github.com/basilfx/pentarm13uxx/master/doc/brd.png)
Board top render

![pcb](https://raw.github.com/basilfx/pentarm13uxx/master/doc/pcb.jpg) Completed boards, photo by [Dirk Soeteman](http://www.dirksoeteman.nl/)