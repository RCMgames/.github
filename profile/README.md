# Welcome to RCMgames.
## Hardware (Robot Control Modules) and Software for building small wifi controlled robots. 

# [Ask questions](https://github.com/orgs/RCMgames/discussions/categories/q-a)
or email robot.control.modules@gmail.com

# [See examples of robots](https://github.com/orgs/RCMgames/discussions/categories/robots)

# Driver Interfaces

### [configurable with text files](https://github.com/RCMgames/RCMDS-new)

### [use Processing and Java to make interfaces for computers and android phones](https://github.com/RCMgames/RCMDS)

# software for ESP32 powered robot control modules

## [RCMv3](https://github.com/RCMgames/RCMv3)
Use a website to configure and program your robot without writing any code.

## [RCMv2](https://github.com/RCMgames/RCMv2)
Template code for your robot, uses PlatformIO/C++/Arduino

## [RCM](https://github.com/RCMgames/RCM) 
Original Arduino code template for the first version of RCM boards.

## useful bits of code are [here](https://github.com/RCMgames/useful-code)
* [useful code for using RCM V4s](https://github.com/RCMgames/RCM-Hardware-V4)
* [useful code for using BYTEs](https://github.com/RCMgames/useful-code/blob/main/boards/RCM-BYTE.h)
* [useful code for using Nibbles](https://github.com/RCMgames/useful-code/blob/main/boards/RCM-Nibble.h)
* [useful code for using original RCMs](https://github.com/RCMgames/useful-code/blob/main/boards/RCM-Original.h)
* [useful code for using RCM D1s](https://github.com/RCMgames/useful-code/blob/main/boards/RCM-D1.h)
* [useful code](https://github.com/RCMgames/useful-code/blob/main/boards/Alfredo_Systems-NOU2.h) for using [Alfredo Systems NoU2s](https://www.alfredosys.com/products/alfredo-nou2/)
* [useful code](https://github.com/RCMgames/useful-code/blob/main/boards/Alfredo_Systems-NOU3.h) for using [Alfredo Systems NoU3s](https://www.alfredosys.com/products/alfredo-nou3/)

# Types of Robot Control Modules

---

## [RCM 1, 2, and 3](https://github.com/RCMgames/RCM_hardware_documentation_and_user_guide) the originals
* 4 motors
* 5 servos
* battery monitoring
* runs from 5 NiMH AA batteries
* all components are hand-solderable through-hole parts
* [get printed circuit boards ("V3")](https://github.com/RCMgames/RCM_hardware_documentation_and_user_guide/tree/main/Robot%20Control%20Module/V3) or [build by hand from a perf board ("V1")](https://github.com/RCMgames/RCM_hardware_documentation_and_user_guide/tree/main/Robot%20Control%20Module/V1)

![image](https://github.com/RCMgames/.github/assets/59814881/db37937a-b7f5-4577-a41f-f9cf68d8a600)

---

## [RCM 4](https://github.com/RCMgames/RCM-Hardware-V4) a better through-hole hand-solderable RCM
* 2 x 3 inches, 50.8 x 76.2 mm
* 4 motors and 7 servos OR 6 motors and 3 servos
* runs from 5 NiMH AA batteries OR (_need to test_) 4.5-20v with the addition of voltage regulators
* all components are hand-solderable through-hole parts
* [Qwiic-Compatible](https://www.sparkfun.com/qwiic#faqs)

<img src="https://github.com/RCMgames/RCM-Hardware-V4/blob/02e49bd58bd07ffe95db38a5303c5c172d2a5ed9/photos/P1040795.JPG" height="35%" width="45%">

---

## [RCM BYTE](https://github.com/RCMgames/RCM-Hardware-BYTE) a smaller yet more capable design
* about 1.25x1.25 inches
* 8 motors
* 8 servos
* battery monitoring
* I2C connector on QT PY
* runs on 3-11 volts

<img src="https://github.com/RCMgames/RCM-Hardware-BYTE/blob/67634be8aeb1c3cb82b1d1cb7a75f85f452896bf/photos/P1040746.JPG" height="35%" width="35%">

---

## [RCM NIBBLE](https://github.com/RCMgames/RCM-Hardware-Nibble) it's half a BYTE
* about 1x1 inches
* 4 motors
* 4 servos
* 2 additional GPIO pins
* built-in IMU
* battery monitoring
* I2C connector on QT PY
* runs on 3-11 volts

<img src="https://github.com/RCMgames/RCM-Hardware-Nibble/blob/5cc9267ceca6876412c50ad4705f115df2f20e71/photos/P1040798.JPG" height="35%" width="35%">

---

## [RCM D1](https://github.com/RCMgames/RCM-hardware-D1) lowest cost RCM
* 1.75 by 1.575 inches, 44.45 by 40.0 millimeters
* 2 motors (one L293D)
* 2 servos OR qwiic connector
* Qwiic-Compatible
* runs on 4 NiMH AAs
* battery monitoring
* uses a Wemos D1 mini with esp8266 CPU

<img src="https://github.com/RCMgames/RCM-hardware-D1/blob/4e2fc0ec890348c75a8239374bd78f8cda3d46ad/Photos/image%201.JPG" height="35%" width="35%">

---

# Components

## [Byte Sized Encoder Decoder](https://github.com/RCMgames/BSCD)
* Reads 8 quadrature encoders
* 1.0x0.85 inches
* I2C (Qwiic Compatible)
* powered by an ATMega328PB
* hand solderable surface mount components

<img src="https://github.com/RCMgames/BSED/blob/1310fdb7eef3eef2137f9add774d0ee8011ccfcf/extras/hardware/photos/P1040733.JPG" height="35%" width="35%">

## other suggested components
https://github.com/RCMgames/useful-code/tree/main/useful-components

# Connect RCM robots to ROS2 using MicroROS
[Example of controlling an omnidirectional robot from ROS2](https://github.com/orgs/RCMgames/discussions/1)

[Other Examples](https://github.com/orgs/RCMgames/discussions?discussions_q=label%3AROS)

# All these boards are also shared on [PCBWay](https://www.pcbway.com/project/member/?bmbno=3A3EE6C1-4199-43)
PCBWay sponsored some of the prototyping runs of these boards. PCBWay provides great customer support and produces good boards.
