# Marlin setup
Backup setup for the custom handmade 3d printer based on version **2.1.2.2** from https://github.com/MarlinFirmware/Marlin 
Board: **Makerbase MKS Robin Nano V3.1**
Motor driver: **TMC2209**

### Board setup path: 
...\platformio.ini

default_envs = mks_robin_nano_v3_1_usb_flash_drive_msc

### Main changes path:
...\Marlin\Configuration.h

### Pins:
...\Marlin\src\pins\stm32f4\pins_MKS_ROBIN_NANO_V3.h
...\Marlin\src\pins\stm32f4\pins_MKS_ROBIN_NANO_V3_common.h