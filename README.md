# Crazyflie Firmware

This project contains the source code for the firmware used in the Crazyflie range of platforms, including the Crazyflie 2.X and the Roadrunner.

## Building and Flashing
The following code is for building and flashing the Crazyflie firmware, and activating the Crazyflie as a WiFi hotspot. In the config menu, the option to enable WiFi can be found in the under 'expansion deck configuration' and then 'Wifi setup at startup'. The option 'Act as access point' should be enabled.
```
sudo apt install build-essential libncurses5-dev
git clone
cd crazyflie-firmware
make menuconfig
make -j12
make cload
```


## Official Documentation

Check out the [Bitcraze crazyflie-firmware documentation](https://www.bitcraze.io/documentation/repository/crazyflie-firmware/master/).
