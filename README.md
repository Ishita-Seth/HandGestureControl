# Hand Gesture Control

This project allows you to control computer functions like volume up/down and next/previous actions using hand gestures detected by an Arduino with an MPU6050 sensor, and a Python script.

## Setup Instructions

### Hardware
- Arduino board
- HC-SR04 sensor
- Jumper wires

### Software
- Arduino IDE
- Python 3
- PySerial
- PyAutoGUI

## Installation

1. **Arduino:**
   - Upload `gesture_control.ino` to your Arduino board.

2. **Python:**
   - Install the required Python packages:
     ```bash
     pip install pyserial pyautogui
     ```
   - Run `gesture_control.py`:
     ```bash
     python gesture_control.py
     ```

## Usage
- Move your hand in front of the sensor to perform actions like volume up, volume down, next, and previous.
