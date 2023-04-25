# Antmicro's OV5640 Dual Camera Board

Copyright (c) 2017-2023 [Antmicro](https://www.antmicro.com)

![OV5640 Dual Camera Board](/img/ov5640-dual-camera-board.png)

## Overview

This project contains open hardware design files for a camera board supporting two [OV5640](https://cdn.sparkfun.com/datasheets/Sensors/LightImaging/OV5640_datasheet.pdf) image sensors from OmniVision. 
These RGB sensors provide a rolling shutter and offer a resolution of 5MP (2591x1944).
The design files for this project are provided and maintained in KiCad.

### Project structure

The main directory contains the KiCad design files, LICENSE and README.
The remaining files are stored in the following directories:

* ``img`` - contains graphics for this README
* ``doc`` - contains generated schematics and other documentation
* ``lib`` - contains KiCad component library

## Key features

* Two OV5640 image sensors placed on a PCB
* Fastening holes spaced by 20mm for a standard S-mount lens holder
* Each sensor is accessible through an independent 2-lane MIPI CSI-2 interface
* Separate I2C buses for sensor configuration 
* Unified, 50-pin FFC interface
* On-board clock generator for driving the image sensors 

The OV5640 Dual Camera board is electrically compatible with a variety of processing platforms created by Antmicro.
Below is a list of a few selected ones:

* [Jetson Nano Baseboard](https://github.com/antmicro/jetson-nano-baseboard) supporting NVIDIA [Jetson Nano](https://developer.nvidia.com/embedded/jetson-nano), Jetson [TX2 NX](https://developer.nvidia.com/embedded/jetson-tx2-nx), Jetson [Xavier NX](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/jetson-xavier-nx/) System on Modules
* [Jetson Orin Baseboard](https://github.com/antmicro/jetson-orin-baseboard) supporting NVIDIA Jetson Orin NX, Jetson Orin Nano
* [Kria K26 Devboard](https://github.com/antmicro/kria-k26-devboard) supporting AMD-Xilinx [KRIA K26](https://www.xilinx.com/products/som/kria/k26c-commercial.html) System on Module
* [Google Coral Baseboard](https://github.com/antmicro/google-coral-baseboard) supporting [Google Coral](https://coral.ai/products/som) System on Module
* [Snapdragon 845 Baseboard](https://github.com/antmicro/snapdragon-845-baseboard) based on Quectel SA800 SoM with Qualcomm [Snapdragon 845 Mobile Platform](https://www.qualcomm.com/products/mobile/snapdragon/smartphones/snapdragon-8-series-mobile-platforms/snapdragon-845-mobile-platform)
* [Snapdragon 625 Baseboard](https://github.com/antmicro/snapdragon-625-baseboard) based on Quectel SC606T SoM with Qualcomm [Snapdragon 625 Mobile Platform](https://www.qualcomm.com/products/mobile/snapdragon/smartphones/snapdragon-6-series-mobile-platforms/snapdragon-625-mobile-platform)

## License

This project is licensed under the [Apache-2.0](LICENSE) license.
