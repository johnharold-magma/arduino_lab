# Laboratory Activities in COSC 111B - CS ELECTIVE 3 (INTERNET OF THINGS) (1st Sem 25-26)

This repository contains our submission for the Laboratory Activities in COSC 111B - CS ELECTIVE 3 (INTERNET OF THINGS) (1st Sem 25-26)

# INTRODUCTION

This repository contains a collection of laboratory activities and examination projects developed for an undergraduate Computer Science course. The projects progress from fundamental microcontroller concepts—such as digital and analog signal processing—to advanced systems involving sensor integration, bidirectional serial communication, and IoT implementation using Python and FastAPI.

The primary goal of this repository is to demonstrate proficiency in embedded systems programming, hardware-software interfacing, and full-stack IoT integration.

## Table of Contents
1. [Laboratory Activity#1: Working with Digital Signals](https://github.com/Hexizen/arduino_lab/tree/main/Laboratory_Activity_1)
2. [Laboratory Activity#2: Working with Analog Signals](https://github.com/Hexizen/arduino_lab/tree/main/Laboratory_Activity_2)
3. [Laboratory Activity #3: Working with Sensors](https://github.com/Hexizen/arduino_lab/tree/main/Laboratory_Activity_3)
4. [Laboratory Activity #4: Arduino Serial Connection](https://github.com/Hexizen/arduino_lab/tree/main/Laboratory_Activity_4)
5. [Laboratory Activity#5: Receiving Serial Connection using Arduino from Python](https://github.com/Hexizen/arduino_lab/tree/main/Laboratory_Activity_5)
6. [Laboratory Activity#6: Bidirectional Control using Arduino and Python](https://github.com/Hexizen/arduino_lab/tree/main/Laboratory_Activity_6)
7. [Laboratory Activity#7: Controllling Arduino using FastAPI](https://github.com/Hexizen/arduino_lab/tree/main/Laboratory_Activity_7)
8. [Laboratory Exams](https://github.com/johnharold-magma/arduino_lab/tree/main/Laboratory_Exams)
    - [Midterm Exam](https://github.com/Hexizen/arduino_lab/tree/main/Laboratory_Exams/Midterm)
    - [Finals Exam](https://github.com/Hexizen/arduino_lab/tree/main/Laboratory_Exams/Finals)

### Files

1. Arduino Code Sketch File (*.ino)
2. Breadboard Diagram (*.png, .jpg)
3. Tinkercad Diagram and Simulation (tinkercard url)
4. Video simulating the breadboard and its corresponding circuit diagram on Tinkercad

### AI
1. Prompts used to transact with your selected Generative AI
2. Model used to generate the content
3. Transaction ID or the link of the conversation


### Necessary Information
- Hardware Requirements

    - Arduino Uno R3 / R4 WiFi

    - LEDs & Resistors (220Ω)

    - Push Buttons & Resistors (10kΩ for pulldown, or internal pullup usage)

    - Sensors: Photoresistor (LDR), NTC Thermistor

    - Piezo Buzzer

- Software & Libraries

    - Arduino IDE: Used for flashing .ino files.

    - Python IDE: Visual Studio Code

    - Python 3.x: Required for serial interfacing scripts.

    - pyserial: For serial communication (pip install pyserial).

    - fastapi, uvicorn: For the web API activity (pip install fastapi uvicorn).

    - requests: For the IoT client (pip install requests).

- Setup Instructions

    - Wiring: Ensure components are wired according to the pin definitions at the top of each .ino file.

    - Port Configuration: When using Python scripts, update the SERIAL_PORT variable (e.g., COM3, /dev/ttyUSB0) to match your connected Arduino device.

    - Baud Rate: Ensure the Serial Monitor and Python scripts are set to 9600 baud (unless specified otherwise in the code).
