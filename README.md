# HexBug

## Description

This project creates a WiFi-controlled robot using the ESP8266 microcontroller, allowing users to control its movements through a mobile application developed with MIT App Inventor. The robot can move in various directions and stop, all through simple commands sent from the app via the cloud.

## Features

- **WiFi Connectivity**: The robot connects to a WiFi network for remote control.
- **Mobile Control**: Control the robot's movements using a mobile application developed with MIT App Inventor.
- **Motor Driver**: Utilizes the L298N motor driver for efficient control of the robot's motors.
- **Simple Commands**: Send commands (`F` for forward, `B` for backward, `L` for left, `R` for right, and `S` for stop) to manage the robot's direction.

## Components Used

- **Microcontroller**: ESP8266
- **Motor Driver**: L298N
- **Mobile App**: Developed using MIT App Inventor

## Getting Started

1. **Hardware Setup**:
   - Connect the ESP8266 to the L298N motor driver according to the circuit diagram.
   - Connect the motors to the L298N.

2. **Software Setup**:
   - Upload the provided Arduino sketch to the ESP8266 using the Arduino IDE.
   - Configure the WiFi credentials in the sketch.
   - Set up the MIT App Inventor project to link with the ESP8266 for sending commands.

3. **Usage**:
   - Power on the robot and connect your mobile device to the same WiFi network.
   - Open the MIT App Inventor application and use the interface to control the robot's movements.

## Conclusion

This project showcases the integration of IoT and mobile app development, providing a platform to learn about remote control systems and motor management using ESP8266 and L298N.
