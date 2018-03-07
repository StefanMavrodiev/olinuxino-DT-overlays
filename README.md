<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [olinuxino-DT-overlays](#olinuxino-dt-overlays)
	- [Feauture overlays](#feauture-overlays)
		- [SPI flash](#spi-flash)
		- [ATEECC508](#ateecc508)
		- [EMAC](#emac)
		- [IR0](#ir0)
	- [LCD overlays](#lcd-overlays)

<!-- /TOC -->

# olinuxino-DT-overlays
Specific device-tree overlays for OLinuXino platform

## Feauture overlays
These overlays are optional features on some boards. They should be enabled
by board ID. For example some boards have SPI Flash, some don't.

### SPI flash
Some boards comes with W25Q128 chip. The flash can be used for booting
bootloader or even for some minimal system.

Boards that use this overlay are:
* A20-OLinuXino-MICRO-sxMB
* A20-OLinuXino-Lime-sxMB
* A20-OLinuXino-Lime2-sxMB
* A20-SOM204-1Gs16Me16G-MC

### ATEECC508
Boards using this overlay are:
* A20-SOM204-1Gs16Me16G-MC

### EMAC
Boards using this overlay are:
* A20-SOM204-1Gs16Me16G-MC

### IR0
Boards using this overlay are:
* A20-SOM204-1Gs16Me16G-MC

## LCD overlays
By default HDMI output is enabled. However there are several DT overlays that
can be used for enabling LCD output:
* [LCD-OLinuXino-4.3TS][1]
* [LCD-OLinuXino-7][2]
* [LCD-OLinuXino-7TS][2]
* [LCD-OLinuXino-10][3]
* [LCD-OLinuXino-10TS][3]


[1]: https://www.olimex.com/Products/OLinuXino/LCD/LCD-OLinuXino-4.3TS/open-source-hardware
[2]: https://www.olimex.com/Products/OLinuXino/LCD/LCD-OLinuXino-7/open-source-hardware
[3]: https://www.olimex.com/Products/OLinuXino/LCD/LCD-OLinuXino-10/open-source-hardware
