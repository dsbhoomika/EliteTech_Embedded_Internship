# Task 3 – Temperature Measurement System

## Objective
Design a system to measure temperature using a sensor and display it on an LCD.

## Components Used
- Arduino UNO
- TMP36 Temperature Sensor
- 16x2 LCD (I2C – MCP23008 based)
- Jumper Wires

## Working Principle
The TMP36 sensor outputs a voltage proportional to temperature. The Arduino reads the analog value from pin A0 and converts it into temperature in Celsius using the TMP36 conversion formula. The calculated temperature value is then displayed on the I2C 16x2 LCD.

## Simulation Platform
Tinkercad Circuits
