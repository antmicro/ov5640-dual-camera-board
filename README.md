# Antmicro's OV5640 Dual Camera Board

Copyright (c) 2017-2023 [Antmicro](https://www.antmicro.com)

![OV5640 Dual Camera Board](/img/ov5640-dual-camera-board.png)

## Overview

This project contains open hardware design files for a camera board supporting two [OV5640](https://cdn.sparkfun.com/datasheets/Sensors/LightImaging/OV5640_datasheet.pdf) image sensors from OmniVision. 
The sensors are RGB ones with rolling shutter and offer a resolution 5MP (2591x1944).
The design files for this project are provided and maintained in KiCad.

### Project structure:

The main directory contains the KiCad design files, LICENSE and README.
The remaining files are stored in the following directories:

* ``img`` - contains graphics for this README
* ``doc`` - contains generated schematics and other documentation
* ``lib`` - contains KiCad component library

## Key features

* Two OV5640 image sensors placed on a PCB
* Fastening holes for standard 22-mm S-mount lens holders
* Each sensor is accessible through an independent 2-lane MIPI CSI-2 interface
* Separate I2C busses for sensor configuration 
* Unified, 50-pin FFC interface
* On-board clock generator for driving the image sensors 

The OV5640 Dual Camera board is electrically compatible with a variety of processing platforms created by Antmicro.
Below there is a list of selected ones

* [Jetson Nano Baseboard]() supporting NVIDIA Jetson Nano, Jetson TX2 NX, Jetson Xavier NX
* [Jetson Orin Baseboard]() supporting NVIDIA Jetson Orin NX, Jetson Orin Nano

## License

This project is licensed under the [Apache-2.0](LICENSE) license.
