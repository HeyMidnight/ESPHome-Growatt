# Description
- The code can be used by putting the Growatt ShineWifi-X into boot mode and flashing it with ESPHome.
- This is a raw ModBus implementation and does not use ESPHome's growatt_solar platform.
- Supports PV1, PV2, battery, grid and EPS load values.
- This configuration pulls data every 5 seconds.
- This code is tested on Growatt SPHXXXXTL BL-UP

# Using the ShineWifi-X
To flash the ShineWifi-X with ESPHome you need to put it into boot mode, by jumping the GPIO0 and GND pins while plugging in/powering on the USB-device.
