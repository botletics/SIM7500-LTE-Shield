## Overview
This shield uses SIMCOM's SIM7500-series 4G LTE CAT-1 module which supports a host of different features. It has integrated GNSS (GPS/GLONASS/BeiDou/Galileo) for location tracking. The shield can be used in different regions around the world simply by choosing the appropriate module version, either the SIM7500A (American), SIM7000C (Chinese), or SIM7000E (European) as detailed in my [Github wiki](https://github.com/botletics/SIM7000-LTE-Shield/wiki/Board-Versions). The shield also includes a high-accuracy I2C temperature sensor for IoT monitoring applications. To use the shield, simply follow the [step-by-step wiki](https://github.com/botletics/SIM7000-LTE-Shield/wiki) to attach the headers, plug the shield into an Arduino, insert a compatible SIM card (like a [Hologram SIM card](https://www.botletics.com/products/hologram-sim)), attach the dual LTE diversity/GPS antenna, power it via micro USB, and you're ready to load the example code!

You can buy the shield on [my website](https://www.botletics.com/products/sim7500-shield)

Check out the [comprehensive wiki]() to get started with setup instructions, example code, and more!

All PCB design files and hardware are released under the [Creative Commons Attribution Share Alike 4.0 license](https://choosealicense.com/licenses/cc-by-sa-4.0/).

All other software is released under the [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/).

## Arduino Library Support
The library in this repo is an altered library built upon the original Adafruit FONA library with added functionality for 2G (SIM800/808/900/908), 3G (SIM5320), SIM7000 LTE CAT-M/NB-IoT module, and SIM7500. As such, it's probably the best Arduino library for SIMCom modules available so far and I've also included examples and library functions focusing on sending data to the cloud via HTTP/HTTPS/MQTT with more functionalities always being tested!

The following list is a summary of the things I've done so far:

### Confirmed functionalities
- Picking up, hanging up, and initiating phone calls
- Voice calling with AT&T SIM card (does not work with Ting SIM though) with microphone and speaker!
- HTTP and HTTPS
- Can send AT commands via USB port
- Getting network time (AT+CCLK?)
- Setting and reading speaker volume
- SMS functions (send/receive SMS, reading number of SMS, reading all SMS, deleting SMS, etc.). Can send and receive texts directly from its phone number!
- Connects on either AT&T and Verizon with Hologram SIM card in the USA
- GPS workss great!
- Generic stuff (read SIM CCID, supply voltage, network connection status, RSSI, etc.)

### To-Do List
- FTP
- MQTT
