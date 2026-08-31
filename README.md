# Earthquake Detector

An Arduino-based vibration detection prototype designed to detect sudden ground vibrations and provide visual and audible alerts.

## About the Project

The Earthquake Detector uses an SW-420 vibration sensor connected to an Arduino Uno.

When vibration is detected, the Arduino processes the sensor signal and activates an LED and buzzer to provide an alert.

## How It Works

1. Ground vibration occurs.
2. The SW-420 vibration sensor detects the vibration.
3. The sensor sends a signal to the Arduino Uno.
4. The Arduino processes the input.
5. The LED and buzzer are activated to alert the user.

## Components Used

- Arduino Uno
- SW-420 Vibration Sensor
- LED
- Buzzer
- Jumper Wires
- Breadboard

## Technologies

- C/C++
- Arduino IDE
- Arduino Uno
- SW-420 Sensor

## Project Structure

```text
earthquake-detector/
│
├── README.md
└── earthquake_detector.ino
