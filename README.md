## Overview
This shield uses SIMCOM's SIM7500-series 4G LTE CAT-1 module with integrated GNSS (GPS/GLONASS/BeiDou/Galileo) for location tracking. The shield can be used in different regions around the world by choosing the appropriate module version, such as the SIM7500A (Americas), SIM7500E (Europe), or SIM7500G (Global) as detailed in the [Github wiki](https://github.com/botletics/SIM7500-LTE-Shield/wiki/Board-Versions). The shield also includes a high-accuracy I2C temperature sensor for IoT monitoring applications. To use the shield, simply follow the [step-by-step wiki](https://github.com/botletics/SIM7500-LTE-Shield/wiki) to attach the headers, plug the shield into an Arduino, insert a compatible SIM card (like a [Hologram SIM card](https://www.hologram.io/)), attach the dual LTE diversity/GPS antenna, power it via micro USB, and you're ready to load the example code!

Check out the shield [on Botletics](https://www.botletics.com/products/sim7500-shield)

Check out the [comprehensive wiki](https://github.com/botletics/SIM7500-LTE-Shield/wiki) to get started with setup instructions, example code, and more!

All PCB design files and hardware are released under the [Creative Commons Attribution Share Alike 4.0 license](https://choosealicense.com/licenses/cc-by-sa-4.0/).

All other software is released under the [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/).

## Arduino Library Support
The library that supports the SIM7500 module can be found on the [SIM7000-Shield-Library repo](https://github.com/botletics/SIM7000-Shield-Library) which is based on the [Adafruit FONA library](https://github.com/adafruit/Adafruit_FONA) and supports a variety of SIMCom 2G/3G/4G LTE/CAT-M/NB-IoT modules, including the SIM7500.
