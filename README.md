# GarageGuard-Smart-Security-System
## Description
This project implements an automated garage system using an AVR microcontroller (ATmega32) and various sensors and actuators. The system includes features such as temperature monitoring and fire alarm functionality, ultrasonic sensors for detecting vehicle presence, servo motors for gate control, LED indicators, and UART communication for remote monitoring. **REFERE BACK TO THE PROJECT DOCUMENTAITON FOR MORE DETAILS**
## Table of Content
1. [Installation](#installation)
2. [Usage](#usage)
3. [License](#license)
4. [Features](#features)
## Installation
- For simulation, I used Protues with added libraries for every sensor, whenever needed. The .Hex file is attached above as well.
- For real-time, I used AVR Atmega32 with LCD and different sensors. **You can find all the sensor images in the Image file attached above** 
## Usage
1. Program the ATmega32 microcontroller with the provided code.
2. Connect the sensors and actuators as described in the hardware setup section.
3. Power up the system and monitor the UART communication for system status and remote control.
## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
## Features
- Temperature monitoring with LM35 sensor.
- Ultrasonic and Infrared Red sensors for vehicle detection.
- Servo motor control for garage gates.
- LED indicators for status display.
- UART communication for remote monitoring.
