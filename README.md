# Crazyflie Firmware  [![CI](https://github.com/bitcraze/crazyflie-firmware/workflows/CI/badge.svg)](https://github.com/bitcraze/crazyflie-firmware/actions?query=workflow%3ACI)

This project contains the source code for the firmware used in the Crazyflie range of platforms, including the Crazyflie 2.X and the Roadrunner.

## Building and Flashing
The following code is for building and flashing the Crazyflie firmware, and activating the Crazyflie as a WiFi hotspot.
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
