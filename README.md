# BluMagx
![](https://img.shields.io/badge/Version-0.9_beta.1-green.svg)

## Bluetooth Remote Controller for Blackmagic Design cameras.

![Banner](blob/banner.jpg?raw=true)

## Tested cameras
* Blackmagic Pocket Cinema Camera 4K/6K https://www.blackmagicdesign.com/products/blackmagicpocketcinemacamera

## Tested M5Stack controllers
* M5Stack ESP32 Basic Core IoT Development Kit https://m5stack.com/collections/m5-core/products/basic-core-iot-development-kit
* M5Stack ESP32 GREY Development Kit with 9Axis Sensor https://m5stack.com/collections/m5-core/products/grey-development-core

# Getting Started

## Prerequisites
* Install CP2104 Driver https://m5stack.com/pages/download
* Download nodemcu-pyflasher software https://github.com/marcelstoer/nodemcu-pyflasher/releases
* Download BluMagx RemoteController firmware https://github.com/IllimarR/BluMagx/releases/

## Installation / flashing
* Connect M5Stack controller to your computer
* Launch nodemcu-pyflasher software
* Select correct Serial port
* Select previously downloaded BluMagx RemoteController firmware file
* Select correct baud rate (suggested to use 11520)
* Select Flash mode Quad I/O (QIO)
* Select Erase flash yes
* Click FlashNodeMCU tp start flashing
* Wait until flashing is complete, remove USB cable from M5Stack controller
* Connect USB power to M5Stack/switch on M5Stack to start Bluetooth Remote Controller

# Screenshots
![Banner](blob/screenshots.jpg?raw=true)

# Donation

If this project helped you and you want support BluMagx development:

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=K624NH2CJ7TXQ&item_name=BluMagx+development+donation&currency_code=EUR&source=url)

# Acknowledgments

- BlackMagic Design's awesome [SDK](https://www.blackmagicdesign.com/developer/product/camera)
- [schoolpost](https://github.com/schoolpost/BlueMagic32) Arduino ESP32 Library for connecting to Blackmagic Cameras using Bluetooth Low Energy
