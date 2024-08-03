# ESP32 CAM Face Detection Door Lock System

## Overview

This project utilizes an ESP32 CAM board along with a relay module and solenoid lock to create a door lock system that automatically unlocks upon recognizing enrolled faces.

## Requirements

For this project, you will need the following components:
- ESP32 CAM board
- UART TTL programmer
- Relay module
- Solenoid lock
- LEDs
- 12V power supply or battery
- 7805 regulator (to provide 5V)
- 100uF 16V capacitor
- Breadboard and wires

## Installation

1. **Setup ESP32 CAM**:
   - Connect the ESP32 CAM to your computer using a UART TTL programmer.
   - Ensure the ESP32 CAM is powered with either a 5V power source or through the 7805 regulator if using a higher voltage supply.
   - Download the modified camera web server example code.
   - Upload the code to the ESP32 CAM using the Arduino IDE or similar software.

2. **Configure WiFi**:
   - Edit the code to include your WiFi SSID and password.
   - Upload the edited code to the ESP32 CAM.

3. **Hardware Connections**:
   - Connect the relay module and solenoid lock to the ESP32 CAM according to the provided wiring diagram.
   - Ensure proper power supply connections using the 7805 regulator if required.

4. **Testing**:
   - Power on the circuit and wait for the ESP32 CAM to start.
   - Access the IP address displayed on the serial monitor through a web browser.
   - Enroll faces by following the on-screen instructions.
   - Test the system by presenting enrolled faces to the camera and verifying if the door unlocks.

## Usage

1. **Enroll Faces**:
   - Navigate to the web interface and click on "Enroll Face".
   - Follow the prompts to capture images of your face for enrollment.

2. **Unlocking**:
   - When a recognized face is detected, the relay module triggers the solenoid lock to open.

## Contributing

Contributions to improve or extend this project are welcome. Fork the repository, make your changes, and submit a pull request.

