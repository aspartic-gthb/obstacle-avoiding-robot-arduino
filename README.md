# Obstacle Avoiding Robot Car 🚗🤖

An Arduino-based obstacle avoiding robot car designed to autonomously detect obstacles using an ultrasonic sensor and navigate by controlling DC motors through a motor driver.

**Project Status: Under Active Development**  
This project is currently in the **early debugging phase**.  
Although all required hardware connections have been completed correctly, **basic motor movement is not functioning as expected**. The issue is being actively investigated.

This repository documents not only the intended design, but also the **troubleshooting and learning process** involved in embedded systems development.

---

## Intended Features
- Autonomous obstacle detection using ultrasonic sensor
- Motor control via motor driver module
- Directional decision making (left / right turn)
- Modular and extensible Arduino code

---

## Components Used
- Arduino Uno (Clone)
- Ultrasonic Sensor (HC-SR04)
- Motor Driver Module (L298N / L293D)
- DC Motors with Robot Chassis
- External Battery Supply
- Jumper Wires

---

## Intended Working Principle
1. Ultrasonic sensor measures distance ahead.
2. Arduino processes distance data.
3. Based on threshold distance:
   - Robot moves forward
   - Stops and changes direction when obstacle is detected
4. Motors are driven using control signals from the motor driver.

---

## Current Status & Issues
- Motors **do not rotate**, even with correct wiring
- Basic forward movement is **not achieved**
- Ultrasonic sensor logic not yet validated due to motor issue

---

## Troubleshooting in Progress
- Verifying motor driver enable and control pins
- Testing motors independently using direct power
- Running isolated motor test codes
- Checking power supply adequacy and common ground
- Verifying Arduino pin mapping and logic levels

Detailed debugging notes are available in `TROUBLESHOOTING.md`.

---

