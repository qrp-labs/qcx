# QCX

More information about the QCX is available here: [QCX](https://www.qrp-labs.com/qcx.html)

This repository is focused on easy access to all firmware versions for this kit.

## Available versions
To be updated 

## Upgrading your firmware

The QCX kit includes a 2 x 3-pin standard AVR header for In-Circuit-Programming on the board. Many suitable AVR programmers are available inexpensively on eBay and elsewhere. They have a USB cable to connect to a PC. On the PC you need software such as avrdude (very popular command line driven tool), or Windows programs with graphical user interfaces to avrdude.exe, for example [Extreme Burner](http://extremeelectronics.co.in/avr-tutorials/gui-software-for-usbasp-based-usb-avr-programmers/), [Bit Burner](https://sourceforge.net/projects/bitburner/), or [AVRDudess](http://blog.zakkemble.co.uk/avrdudess-a-gui-for-avrdude/). All are free. When upgrading the firmware, ensure:

1) Only use an original QRP Labs QCX firmware chip
2) Program only the provided .hex file; do not change the Fuse settings, or other memories (e.g. EEPROM).

Simon VK3ELH wrote [a tutorial](https://www.qrp-labs.com/images/qcx/HowToUpdateTheFirmwareOnTheQCXusingAnArduinoUNOandAVRDUDESS.pdf) on how to use an Arduino UNO and the AVRDudess program to update your QCX firmware.


## Acknowledgments

This repository is just an easier way to access firmware written by [Hans Summers](http://www.hanssummers.com) for the [QCX](https://www.qrp-labs.com/qcx.html)
