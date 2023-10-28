# Driver Health Monitoring System

## Introduction
The Driver Health Monitoring System is a comprehensive solution designed to enhance road safety by continuously monitoring the vital signs of a driver. Utilizing various sensors and an Arduino board, this system tracks health parameters in real-time, ensuring that any anomalies are immediately detected, potentially preventing accidents due to health emergencies.

## Features
- Continuous monitoring of the driver’s heart rate and blood oxygen level using MAX30100 Pulse Oximeter.
- Monitoring of ambient and object temperature using Adafruit MLX90614.
- Bluetooth connectivity for real-time data transmission.
- Immediate alert system for quick response.
- Drowsiness detection through machine learning integration (in a separate repository).

## Repository Contents
- **maincode**: The Arduino code required to set up the monitoring system with the necessary sensors.
- **README.md**: Project documentation.

## Hardware Requirements
- Arduino Board
- MAX30100 Pulse Oximeter
- Adafruit MLX90614 IR Thermometer
- HC-05 Bluetooth Module
- Jumper Wires
- (Any other hardware components you’ve used for the project)

## Prerequisites
- Arduino IDE
- Necessary Arduino libraries: Wire, MAX30100_PulseOximeter, Adafruit_MLX90614, SoftwareSerial

## Installation
1. Install Arduino IDE on your computer.
2. Open Arduino IDE and navigate to `Sketch > Include Library > Manage Libraries`.
3. Install the required libraries:
    - MAX30100 by OXullo Intersecans
    - Adafruit MLX90614 Library
4. Connect the hardware components as per the circuit diagram (please provide a circuit diagram if possible).
5. Clone this repository to your local machine.
6. Open the `maincode.ino` file in Arduino IDE.
7. Connect the Arduino board to your computer.
8. Select the correct board and port in Arduino IDE.
9. Upload the code to the Arduino board.

## Usage
After successfully uploading the code to the Arduino board and setting up the hardware:
1. Open the Serial Monitor in Arduino IDE to view the health data.
2. Connect a Bluetooth module to the Arduino board to enable wireless data transmission.
3. Pair the Bluetooth module with your device to receive the health data.

## Technologies Used
- Arduino IDE: Used for programming the Arduino board.
- MAX30100 Pulse Oximeter: Used for monitoring heart rate and blood oxygen level.
- Adafruit MLX90614 IR Thermometer: Used for measuring ambient and object temperature.
- HC-05 Bluetooth Module: Used for wireless data transmission.

## Driver Drowsiness Detection
This system works in conjunction with a Driver Drowsiness Detection System implemented using machine learning. The Drowsiness Detection System analyzes the driver’s facial features in real-time to detect signs of drowsiness and alert the driver accordingly.

For more information and to access the machine learning model, please visit the [Driver Drowsiness Detection System Repository](https://github.com/TekeshwarHirwani/machine-learning-projects/tree/main/Driver_drowsiness).

## Contributing
Feel free to fork this repository, and submit a pull request if you'd like to contribute to the development of the Driver Health Monitoring System.


## Contact
If you have any questions or would like to connect regarding this project, please reach out via email at hirwanitekeshwar@gmail.com or connect with me on [LinkedIn](https://www.linkedin.com/in/tekeshwar-hirwani).

Thank you for your interest in the Driver Health Monitoring System!
