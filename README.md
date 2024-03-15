# Crazyflie Firmware

This project contains the source code for the firmware used in the Crazyflie range of platforms, including the Crazyflie 2.X and the Roadrunner.

## Building and Flashing
The following code is for building and flashing the Crazyflie firmware and activating the Crazyflie as a WiFi hotspot. In the config menu, the option to enable WiFi can be found under 'expansion deck configuration' and then 'Wifi setup at startup'. The option 'Act as access point' should be enabled. The only two files different from the original firmware are locodeck.c and aideck.c. Both of these are located in crazyflie-firmware/src/deck/drivers/src/. For using a newer version of the firmware, download and copy these two files in the appropriate directory. These files have been altered as a workaround for combining the AI deck and Loco positioning deck. 
```
sudo apt install build-essential libncurses5-dev
git clone https://github.com/BNoordam/crazyflie-firmware
cd crazyflie-firmware
make menuconfig
make -j 12
make cload
```


## Official Documentation

Check out the [Bitcraze crazyflie-firmware documentation](https://www.bitcraze.io/documentation/repository/crazyflie-firmware/master/).
