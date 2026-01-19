# Laboratory Activity#6: Bidirectional Control using Arduino and Python

This repository contains our submission for Laboratory Activity#6: Bidirectional Control using Arduino and Python

## Table of Contents
1. [Description](#description)
2. [Files Description](#files)
3. [Generative AI](#ai)
4. [Grades](#grades)

## Description
This system establishes a two-way handshake between the microcontroller and a Python script.

- Components: RGB LED (Pins 5, 6, 7), 3 Push Buttons (Pins 10, 11, 12).

- Logic:

    - Inbound (Python to Arduino): Python sends numeric commands ('1', '2', '3') to toggle the respective LEDs on the Arduino.

    - Outbound (Arduino to Python): Pressing physical buttons on the Arduino sends character signals ('R', 'G', 'B') to Python. Python detects these signals and echoes back a command to toggle the corresponding LED, confirming the loop.

## Files
1. Arduino Code Sketch File (*.ino)
2. [Breadboard Diagram](https://drive.google.com/file/d/1KUmylDS3eLIGeaacaXLmm_PzmPTtbrf9/view?usp=sharing)
3. [Tinkercad Diagram]()
4. [Video Simulating the Breadboard and its corresponding Circuit Diagram on TinkerCad]()

## AI
1. [Prompts used to transact with your selected Generative AI]()
2. Model used to generate the content: Gemini 3 Pro
3. [Transaction ID or the link of the conversation](https://gemini.google.com/share/2d25879716f8)

## Grades
- **Leader:**  Rachelle Yazmhine C. Mendez
### Members 
- Jemuel Chris N. Ambong
- Betina B. Arrojo
- Keren G. Dellosa
- John Harold R. Magma
- Jamil S. Mariano
- Audric P. Pascual
