# LiFi-Hazard-Detection

## Li-Fi Hazard Detection Prototype

Li-Fi or Light Fidelity is a wireless communication technology that utilizes light to transmit data and information among different devices. This GitHub repository hosts the code and documentation for a Li-Fi Hazard Detection Prototype. The project involves building a small prototype (Sender + Receiver) for hazard detection in homes using Li-Fi technology.

### Project Features

- **Sender Platform (TM4C123GH6PM) with MCAL:**
  - DIO (Digital Input/Output)
  - ADC (Analog-to-Digital Converter)
  - PWM (Pulse Width Modulation)
  - UART (Universal Asynchronous Receiver-Transmitter)
  - Systick
  - GPTM (General-Purpose Timer Modules)

- **Hardware Abstraction Layer (HAL) with MCAL for:**
  - Temperature Sensor
  - Ultrasonic Sensor
  - Bluetooth Module
  - Magnetic Sensor

- **Receiver (Arduino) Components:**
  - LDR (Light-Dependent Resistor) Module
  - Buzzer
  - LCD Display

- **Main Application Logic:**
  - Integration of MCAL and HAL components for hazard detection.
  - Li-Fi communication for transmitting data.
  - Alarms activation: buzzer and LCD display.
  - Bluetooth communication to a mobile app for remote monitoring.
  - User interface with two pushbuttons for start/stop operations.
  - Mute pushbutton to silence alarms after detection.
  - Detailed system layout, list of components, circuits wiring, and mobile app discussion in the report.
  - Flow charts or pseudo-codes illustrating the main program flow.
  - Group members' contributions outlined in the report.
  - Documentation of problems faced and their solutions.

### Getting Started

1. Clone the repository to your local machine.
2. Explore the source code files in the project folder.
3. Feel free to contribute, report issues, or suggest improvements.

