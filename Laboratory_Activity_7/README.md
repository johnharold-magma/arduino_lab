# Laboratory Activity #7: Controllling Arduino using FastAPI

This repository contains our submission for Laboratory Activity#6: Bidirectional Control using Arduino and Python

## Table of Contents
1. [Description](#description)
2. [Files Description](#files)
3. [Generative AI](#ai)
4. [Grades](#grades)

## Description
An IoT prototype allowing hardware control via a web API.

- Components: RGB LED (Pins 5, 6, 7), Push Buttons (Pins 10, 11, 12).

- Logic:

    - Arduino: Listens for serial commands to control LEDs and reports button presses back to the serial port.

    - Python (FastAPI): Exposes HTTP endpoints (e.g., GET /led/red). When an API request is received, the Python backend forwards the instruction to the Arduino via serial. This allows the hardware to be controlled by a web browser or external software (e.g., Postman).

## Files
1. Arduino Code Sketch File (*.ino)
2. [Breadboard Diagram](https://drive.google.com/file/d/1Q3zFuCz7QvvBWlbJawcrUMuBVxw60YCQ/view?usp=sharing)
3. [Tinkercad Diagram](https://drive.google.com/file/d/1tojCrI2181WEdm6Mzi5x53-089rF7d_4/view?usp=sharing)
4. [Video Simulating the Breadboard and its corresponding Circuit Diagram on TinkerCad](https://drive.google.com/file/d/1DQ9WWUWmo1qZMCe8QqU39jhmn8ZmGocY/view?usp=sharing)

## AI
1. [Prompts used to transact with your selected Generative AI](https://docs.google.com/document/d/1MN57WclmEDDDeA7Bta_moRSLxrkAH41zfC28ILxsMrw/edit?tab=t.0)
2. Model used to generate the content: Gemini 3 Pro
3. [Transaction ID or the link of the conversation](https://gemini.google.com/share/3e477ec98a37)

## Grades
- **Leader:**  Betina B. Arrojo
### Members 
- Jemuel Chris N. Ambong
- Betina B. Arrojo
- Keren G. Dellosa
- John Harold R. Magma
- Jamil S. Mariano
- Rachelle Yazmhine C. Mendez

- Audric P. Pascual
