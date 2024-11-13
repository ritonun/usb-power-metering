
## Introduction
Small USB power metering to monitor charging cycle of small electronics objects. Mostly made for my bicycle light.

![](attachments/block-diagram-usb-power-metering.png)

## BOM
- Power metering: INA219 by Texas Instrument (cheap), 0.63$
- µC: ATmega328p by Microchip (chosen due to ease of programming with an arduino board around), 3.16$
- Display: Controlled by I2C
- USB Controller (for USB-C PD): HUSB238 by Hynetek (cheap, small & adapted to current project), 0.57$

## Power metering
![](attachments/INA219-typical-applications-circuit.png)

## USB-C Controller

## References
[HUSB238](https://www.hynetek.com/uploadfiles/site/219/news/aabbbbdb-48c9-4a44-a6dc-2c15f53282e6.pdf)
[INA219](https://www.ti.com/lit/ds/symlink/ina219.pdf)
