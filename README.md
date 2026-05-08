# Traffic Light Control System using Arduino UNO

This project implements a traffic light control system using an Arduino UNO 
microcontroller programmed in C. The system simulates real-world traffic light 
sequencing with timed transitions between Red, Yellow, and Green signals.

## Features
- Sequential traffic light control (Red → Yellow → Green)
- Timed delays for realistic signal transitions
- Simple and efficient GPIO-based LED control
- Easily modifiable timing parameters

## Components Used
- Arduino UNO
- Red, Yellow, Green LEDs
- Resistors
- Breadboard and jumper wires

## Tools Used
- Arduino IDE

## How It Works
The Arduino UNO controls three LEDs representing traffic signals. Each LED is 
connected to a digital GPIO pin and is turned on/off sequentially with defined 
time delays to simulate a real traffic light cycle.
