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

### Integration of MCAL and HAL Components:

Combine Microcontroller Abstraction Layer (MCAL) and Hardware Abstraction Layer (HAL) components for efficient hazard detection.

### Li-Fi Communication:

Utilize Li-Fi technology for reliable data transmission between the sender and Arduino receiver platform.

### Alarms Activation:

Trigger alarms, including a buzzer and LCD display, upon detection of potential hazards.

### Bluetooth Communication with Mobile App:

Establish Bluetooth communication with a mobile app created using App Inventor for remote monitoring.

### User Interface Controls:

Incorporate a user-friendly interface with two pushbuttons for start/stop operations.

### Mute Pushbutton:

Implement a mute pushbutton to silence alarms after hazard detection.

### UART Communication with App Inventor:

Add UART communication to the mobile app created with App Inventor to display alerts and enhance user interaction.

### Getting Started

1. Clone the repository to your local machine.
2. Explore the source code files in the project folder.
3. Feel free to contribute, report issues, or suggest improvements.
