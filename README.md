# Object Following Car 🚗

An autonomous robot car built using Arduino Uno, ultrasonic and infrared sensors. The car detects and follows an object automatically using sensor-based movement control.

## Project Overview

The main goal of this project is to develop a four-wheel robot car that can detect and follow an object placed in front of it.

The Arduino reads sensor data and controls the motors through an L293D Motor Driver Shield.

## Features

- Automatic object detection
- Object following using ultrasonic distance measurement
- Left and right detection using IR sensors
- Automatic forward, left and right movement
- Automatic stopping when the object is out of range
- Four-wheel DC motor control

## Hardware Components

| Component | Quantity |
|---|---:|
| Arduino Uno R3 | 1 |
| L293D Motor Driver Shield | 1 |
| HC-SR04 Ultrasonic Sensor | 1 |
| FC-51 IR Sensor | 2 |
| SG90 Servo Motor | 1 |
| DC Gear Motors | 4 |
| 18650 Li-ion Batteries | 2 |
| Four-wheel chassis | 1 |
| Jumper Wires | As required |

## Technologies Used

- Arduino IDE
- C/C++
- Embedded Systems
- Robotics
- Sensor Interfacing

## Working Principle

1. The HC-SR04 ultrasonic sensor measures the distance to the object.
2. Two FC-51 IR sensors detect objects on the left and right sides.
3. Arduino Uno processes the sensor readings.
4. The L293D Motor Driver Shield controls the four DC motors.
5. The car moves forward when an object is detected within 1–15 cm.
6. The car turns left or right based on the IR sensor readings.
7. The car stops when the object is outside the following range.

## Pin Connections

| Device | Arduino Pin |
|---|---|
| Ultrasonic Trigger | A1 |
| Ultrasonic Echo | A0 |
| Right IR Sensor | A2 |
| Left IR Sensor | A3 |
| SG90 Servo Signal | D10 |
| Motor 1 | Shield M1 |
| Motor 2 | Shield M2 |
| Motor 3 | Shield M3 |
| Motor 4 | Shield M4 |

## Required Arduino Libraries

- NewPing
- Servo
- AFMotor

## Project Structure

```text
object-following-car/
├── README.md
├── .gitignore
├── LICENSE
├── src/
│   └── object_following_car.ino
├── docs/
│   ├── project-report.tex
│   └── project-report.pdf
└── images/
    ├── project-car.jpg
    ├── circuit-diagram.png
    └── block-diagram.png
```

## Project Team

1. Abir
2. Arif
3. Mamun
4. Shanto
5. Plaboni
6. Nasifa
7. Azhar

## Academic Information

**Institution:** Sylhet International University

**Department:** Computer Science and Engineering

**Course:** Electronic Devices and Circuits

**Project Title:** Object Following Car

**Submission Date:** 03 November 2026

## Future Improvements

- PID-based movement control
- Bluetooth and Wi-Fi connectivity
- Camera-based object tracking
- Improved obstacle avoidance
- Battery level monitoring

## License

This project is intended for educational and academic purposes.
