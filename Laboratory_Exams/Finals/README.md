# Finals Laboratory Exam

This repository contains our submission for Finals Laboratory Exam

## Table of Contents
1. [Description](#description)
2. [Files Description](#files)
3. [Generative AI](#ai)
4. [Grades](#grades)

## Description
A client-side IoT implementation that triggers remote server actions based on hardware input.

- Components: Push Button (Pin 2).

- Logic:

    - Arduino: Detects a button press (debounced) and sends a specific group identifier ("2") via Serial.

    - Python: Constantly listens to the serial port. Upon receiving the group ID, it constructs an HTTP GET request to a remote server (http://172.20.10.3:8000/led/group/2/toggle), effectively functioning as a physical IoT trigger for a networked application.

## AI
1. [Prompts used to transact with your selected Generative AI](https://docs.google.com/document/d/1Ph4f8GnvtJRS32F7EDq53SKSUNrVf3dXvfsSIAUVcg0/edit?usp=sharing)
2. Model used to generate the content: Gemini 3 Pro
3. [Transaction ID or the link of the conversation](https://gemini.google.com/share/cd19b5a6c23a)

## Grades
- **Leader:**  John Harold R. Magma
### Members 
- Jemuel Chris N. Ambong
- Betina B. Arrojo
- Keren G. Dellosa
- Jamil S. Mariano
- Rachelle Yazmhine C. Mendez
- Audric P. Pascual