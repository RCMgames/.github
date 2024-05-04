# Welcome to RCMgames.
## Hardware (Robot Control Modules) and Software for building small wifi controlled robots. 

# [Ask questions](https://github.com/orgs/RCMgames/discussions/categories/q-a)
or email robot.control.modules@gmail.com

# [See examples of robots](https://github.com/orgs/RCMgames/discussions/categories/robots)

# Driver Interfaces

### [configurable with text files](https://github.com/RCMgames/RCMDS-new)

### [use Processing and Java to make interfaces for computers and android phones](https://github.com/RCMgames/RCMDS)

# software for ESP32 powered robot control modules
## [RCMv2](https://github.com/RCMgames/RCMv2)

[RCM](https://github.com/RCMgames/RCM) old code for the original boards

## useful bits of code are [here](https://github.com/RCMgames/useful-code)

# Types of Robot Control Modules

## [RCM 1, 2, and 3](https://github.com/RCMgames/RCM_hardware_documentation_and_user_guide) the originals
* 4 motors
* 5 servos
* battery monitoring
* runs from 5 NiMH AA batteries
* all components are hand-solderable through-hole parts
* [get printed circuit boards ("V3")](https://github.com/RCMgames/RCM_hardware_documentation_and_user_guide/tree/main/Robot%20Control%20Module/V3) or [build by hand from a perf board ("V1")](https://github.com/RCMgames/RCM_hardware_documentation_and_user_guide/tree/main/Robot%20Control%20Module/V1)

![image](https://github.com/RCMgames/.github/assets/59814881/db37937a-b7f5-4577-a41f-f9cf68d8a600)

## (under development) [RCM 4](https://github.com/RCMgames/RCM-Hardware-V4) a better through-hole hand-solderable RCM
* 4 motors and 7 servos OR 6 motors and 3 servos
* runs from 5 NiMH AA batteries OR (_need to test_) 4.5-20v with the addition of voltage regulators
* all components are hand-solderable through-hole parts
* [Qwiic-Compatible](https://www.sparkfun.com/qwiic#faqs)

<img src="https://github.com/RCMgames/RCM-Hardware-V4/blob/67813489e1e16a104faf787c31854115694284c5/CAD%20renders/render%201.jpg" height="35%" width="35%">

## (under development) [RCM BYTE](https://github.com/RCMgames/RCM-Hardware-BYTE) a smaller yet more capable design
* about 1.25x1.25 inches
* 8 motors
* 8 servos
* battery monitoring
* I2C connector on QT PY
* runs on 3-11 volts

<img src="https://github.com/RCMgames/.github/assets/59814881/72edcbcd-33c1-4e90-968b-ed3cd186c1d5" height="35%" width="35%">

## (under development) [RCM NIBBLE](https://github.com/RCMgames/RCM-Hardware-Nibble) it's half a BYTE
* about 1x1 inches
* 4 motors
* 4 servos
* 2 additional GPIO pins
* built-in IMU
* battery monitoring
* I2C connector on QT PY
* runs on 3-11 volts

<img src="https://github.com/RCMgames/.github/assets/59814881/5b6057ba-f43c-48b3-ad4a-4988f07bd62f" height="35%" width="35%">

# Components

## (under development) [Byte Sized Encoder Decoder](https://github.com/RCMgames/BSCD)
* Reads 8 quadrature encoders
* 1.0x0.85 inches
* I2C (Qwiic Compatible)
* powered by an ATMega328P
* hand solderable surface mount components


<img src="https://github.com/RCMgames/.github/assets/59814881/ba19df86-09fd-403e-b5a3-6dda2ad8a977" height="35%" width="35%">

# Connect RCM robots to ROS using MicroROS
[Example of controlling an omnidirectional robot from ROS2](https://github.com/orgs/RCMgames/discussions/1)

