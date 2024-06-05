# Microcontroller-Design-Project-

This project is part of the IA 2209 - Microcontroller Laboratory course. 
It involves creating a microcontroller-based temperature monitoring system with various features including temperature display, alarm, and range indication using LEDs.

## Features

- **Temperature Display**: Displays the current temperature on a 7-segment display with the ability to switch between Celsius and Fahrenheit.
- **Temperature Alarm**: An alarm system that triggers when the temperature exceeds 40°C.
- **Temperature Range Indication**: LEDs indicate different temperature ranges with varying brightness.
- **Mode Switching**: Toggle between displaying temperature and temperature range.

## Components

- ATmega328P Microcontroller
- MAX7219CNG
- 7-segment displays
- LEDs
- Push buttons
- Resistors, capacitors, and other supporting components

## Usage

1. **Compile and Upload Code**: Compile the provided C/C++ code and upload it to the ATmega328P microcontroller.
2. **Hardware Setup**: Connect the hardware components as per the circuit diagram provided in `hardware/circuit_diagram.png`.
3. **Operating the System**:
   - Use the increment and decrement buttons to adjust the temperature.
   - The current temperature is displayed on the 7-segment display.
   - The alarm LED blinks if the temperature exceeds 40°C and can be acknowledged with the acknowledgment button.
   - LEDs indicate the current temperature range.

## File Structure

```plaintext
Temperature-Monitor-Project/
├── src/                 # Source code files
├── include/             # Header files
├── hardware/            # Hardware design files
├── simulations/         # Simulation files
├── docs/                # Documentation files
├── LICENSE              # License file
└── README.md            # Project overview and instructions