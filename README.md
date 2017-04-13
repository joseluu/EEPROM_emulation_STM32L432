# EEPROM_emulation_STM32L432

The EEPROM emulation in the STM32 Cube repository from ST is geared towards the STM32L476 chip, uses the dual bank flash feature
not available in the STM32L432.

This is an adaptation to the STM32L432 with a modification to allow storage of 32 bit values instead of 16 bit.

Compile with make and this toolchain: http://gnutoolchains.com/arm-eabi/
