# 🌡️ ADC Temperature Sensing Using LM35 with LCD Display

## 📌 Project Overview
This project measures ambient temperature using the LM35 temperature sensor and displays the measured value on a 16x2 LCD. The LM35 provides an analog output voltage proportional to temperature, which is converted into digital data using the microcontroller's built-in ADC.

## 🎯 Objective
To demonstrate how an Analog-to-Digital Converter (ADC) is used to read analog sensor data and display processed temperature values on an LCD screen.

## 🛠️ Components Required
- LM35 Temperature Sensor
- pic16f877a
- 16x2 LCD Display
- 10k resistor
- Breadboard
- Jumper Wires
- USB Cable

## ⚙️ Working Principle
- The LM35 outputs 10mV per °C.
- The Arduino reads the analog voltage using its built-in ADC.
- The ADC converts the analog signal into digital values (0–1023).
- The program calculates temperature in °C.
- The temperature is displayed on the 16x2 LCD in real time.

## 🔌 Connections
### LM35:
- VCC → 5V
- GND → GND
- OUT → A0 (Analog Pin)

### LCD (16x2):
- Connect in 4-bit mode to Arduino digital pins
- Use a 10k potentiometer to adjust contrast

## 📌 Applications
- Room temperature monitoring
- Weather stations
- Industrial temperature control
- Electronics overheating protection
