# ASMboot

Small Arduino UNO/ATmega328/P bootloader with full optiboot functionality (https://github.com/Optiboot/optiboot) written in assembler

'ready to burn'

256 words/512 bytes (minimum bootloader size on ATmega328) 

ASMboot features some extras:

- read/write EEPROM
- auto increment address
- read SIGNATURE from MCU
- read/write LOCK bits
- read FUSES
- read oscillator calibration byte
- leave MCUSR reset status in R2
- WRITE_FLASH_PAGE function for user application

'ASMboot_328_16' is for ATmega328/P running on 5,0 V at 16 MHz communicating with 115.200 baud

'ASMboot_328_8' is for ATmega328/P running on 3,3 V at 8 MHz communicating with 57.600 baud

Easy to port to ATmega48/88/168/P
