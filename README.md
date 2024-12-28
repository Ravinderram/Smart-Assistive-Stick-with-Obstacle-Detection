# Smart-Assistive-System-with-Obstacle-Detection
## Overview 
The Smart Assistive Stick is an innovative project designed to assist visually impaired individuals. It features an ultrasonic sensor for detecting obstacles, a DFPlayer Mini module for providing audio feedback, and a servo motor for mechanical movement. The system alerts users to nearby obstacles, enhancing mobility and ensuring safety.

![blind project](https://github.com/user-attachments/assets/06471de1-1bf8-4a0a-88fb-0d27e62aa430)

## Features 
- **Obstacle Detection**: Detects obstacles using an ultrasonic sensor.
- **Audio Feedback**: Provides real-time alerts via sound using the DFPlayer Mini module.
- **Compact Design**: Components are integrated into a portable setup.
- **Customizable**: Easily modifiable for additional features like wireless communication or vibration feedback.
## Components used for the project 
1. Arduino Board (e.g., Arduino Uno)
2. Ultrasonic Sensor (HC-SR04)
3. DFPlayer Mini Module
4. Servo Motor
5. Speaker
6. Power Supply (e.g., 9V battery or power bank)
7. Jumper wires and connectors

## How it works 
1. The ultrasonic sensor detects obstacles within a specified range (100 CM).
2. The distance data is processed by the Arduino.
3. If an obstacle is detected, the DFPlayer Mini generates an audio alert.
4. The servo motor performs necessary movements if additional actions are required.
## Steps
  1. Clone the repository :
  ```bash
 git clone  https://github.com/Ravinderram/Smart-Assistive-Stick-with-Obstacle-Detection.git
 cd Smart-Assistive-Stick-with-Obstacle-Detection
```
2. Run the BPD.ino file into Arduino  IDE
  ``` bash
  BPD.ino
  ```
## Setup Instructions
1. Assemble the components as per the circuit diagram provided.
2. Upload the Arduino code (BPD.ino) to the Arduino board using the Arduino IDE.
3. Power the system using a battery or power source.
4. Test the system by bringing objects into the ultrasonic sensor's range.
## Future Enhancements
- Miniaturizing the system for a pocket-sized design.
- Integrating wireless communication (e.g., Wi-Fi or Bluetooth).
- Adding vibration feedback for silent alerts.
## Contributions 
Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request or open an issue.

