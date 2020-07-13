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

![Banner](blob/screenshots.jpg?raw=true)

# Acknowledgments

- BlackMagic Design's awesome [SDK](https://www.blackmagicdesign.com/developer/product/camera)
- [nkolban](https://github.com/nkolban/esp32-snippets/tree/master/cpp_utils/tests/BLETests/Arduino) BLE examples
- [schoolpost](https://github.com/schoolpost/BlueMagic32) Arduino ESP32 Library for connecting to Blackmagic Cameras using Bluetooth Low Energy
