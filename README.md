# Fire, Gas and Sound Detection System (ESP32)

This project implements a real-time safety monitoring system using an ESP32 microcontroller.
It detects:
- Gas leakage (MQ-6 sensor)
- Fire/flame presence
- Unusual sound events (loud bang or scream)

## Features
- LCD status display
- Audible and visual alarms (buzzer + LED)
- Remote monitoring via Blynk IoT platform
- Wi-Fi connectivity

## Hardware Used
- ESP32 DevKit
- MQ-6 Gas Sensor
- Flame Sensor
- Sound Sensor (Analog + Digital)
- I2C 16x2 LCD
- Buzzer
- LED + resistor
- Breadboard & jumper wires

## Blynk Virtual Pins
- V0 / V3 – Gas level (PPM)
- V1 – Flame status
- V4 – Sound status

## Setup
1. Install required libraries:
   - Blynk
   - LiquidCrystal_I2C
2. Insert your Wi-Fi and Blynk credentials in the code.
3. Upload the sketch to the ESP32.

## Author
Breyn Najoli
