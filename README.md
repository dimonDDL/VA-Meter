# VA Meter
## V2.0 develpmot repository
### Implementing the following:
* Automatic range switching with relays
* Alternative display options
* More on dsevice settings
* Automatic "artifact" calibration

A simple 4 channel V/A meter capable of measuring -50V to 50V, 1mA to 500mA and 1uA to 1000uA. Based on the ADS1015 with specific input resistors to configure the ranges. The code is pretty self explanatory as is the hardware, for best results it is recommended to calibrate the values by using the constants at the top of the main.cpp file. This project was made using PlatformIO, so it is recommended you open it with that, but renaming the file to main.ino and installing all the Arduino libraries manually will also work.
