# LED Brightness Control using Push Buttons (Arduino Project)

A simple Arduino project to control the brightness of an LED using two push buttons. One increases brightness, the other decreases it using PWM (analogWrite).

## Skills Demonstrated
- Digital input (buttons)
- PWM control using analogWrite
- Embedded logic with Arduino C++
- Real-world circuit building and testing

## Components Used
- Aurdino UNO
- 1 LED
- 2 Push Buttons
- 2x 10k&Omega; resistors
- 1 220&Omega; resistor for LED
- Breadboard and jumper wires

## Circuit Summary
- Button 1 (D7) : Increases brightness
- Button 2 (D6) : Decreases brightness
- LED on pin D3 (PWM)
- Resistors act as pull-ups

## Arduino Code
[See 'led_brightness_control.ion' in this reposistory.](https://github.com/aryanpatil-me/led-brightness-control/blob/main/led_brightness_control.ion)

## Circuit Image
![circuit_diagram](https://github.com/user-attachments/assets/4a26c6d6-33b6-49d3-9b33-b56a96a5ece2)

## What I Learned from This Project

This project helped me strengthen both my hardware and programming skills using Arduino. 
Key things I learned:

### Technical Concepts
- **PWM (Pulse Width Modulation):** Used `analogWrite()` to control LED brightness.
- **Digital Inputs:** Read button states using `digitalRead()`.
- **Microcontroller Logic:** Wrote conditional logic to control LED behavior.
- **Debouncing (Basic):** Managed multiple button presses using delay.
- **Pin Configuration:** Assigned digital pins for input (buttons) and output (LED).

### Hardware Skills
- Built a working breadboard circuit using push buttons, an LED, and resistors.
- Understood how to use **pull-up resistors**.
- Connected and tested physical components with the Arduino UNO.

### Practical Outcomes
- Gained confidence working with real components.
- Learned to upload and version control a project on GitHub.
- Practiced documenting projects professionally.


---

Created by **Aryan Patil**
