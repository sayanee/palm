# Palm

> Measure UV index outdoors with a keychain 🗝 hanging on a backpack 🎒. Users can view the current UV index on their mobile app or on-board RGB LED.

- **Wireless:**	BLE
- **Sensors:**	1 (`VEML6075` for UV)
- **Power:**	[LiPo](power.md)
- **Processor:**	`NRF52` on [Adafruit Bluefruit LE](https://www.adafruit.com/product/2661)
- **Modules:** 2 (MCU, sensor)
- **Firmware:**	[Arduino NRF52](https://github.com/sandeepmistry/arduino-nRF5)
- **OTA?**	No
- **Works without connectivity?**	Yes. Display an RGB LED on-board
- **BOM Total Items:**	*Pending*
- **BOM Unique Items:** *Pending*
- **PCB Manufacturing vendor:**	*Pending*
- **BOM vendors:** *Pending*
- **Total vendors:** *Pending*
- **Total units:** 1
- **Total cost:** *Pending*
- **Battery life:** *Pending*
- **Total schedule:** *Pending*

## Getting Started

1. Wire up the [hardware](hardware) components

    ![](hardware/images/schematic.png)
    ![](images/prototype-2.jpg)
1. Flash the [firmware](firmware/firmware.ino) to display UV

    ![](images/console.png)
1. See the UV, temperature and humidity values values being displayed on the [nRF Connect iPhone app](https://itunes.apple.com/sg/app/nrf-connect/id1054362403?mt=8) or the console

    ![](images/ios-detect.jpg)
    ![](images/ios-services.jpg)
    ![](images/ios-characteristics.jpg)

## Others

- [Hardware](hardware)
- [Firmware](firmware)
- Bill of Materials - *Pending*
- [Design](design)
- [Power](power.md)
- [Mechanical](mechanical.md)
- [Schedule](schedule.md)
- Live log - *Pending*
- Lessons Learnt - *Pending*
- [References](references.md)
