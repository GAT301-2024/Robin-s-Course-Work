# OMIYA_ROBIN-23/U/2339/GIW/PS

# Distance Motion Scan Using A Radar
## Overview
This distance motion range scanner is a security based project that detects motion and then its display on a radar scanner using a red spot print. This is achieved when a person moves 5 meters next to the door side and this was achieved using an arduino board, ultrasonic sensor, buzzer for alerting and servo motor that is embedded on to the ultrasonics.

## Hardware Components
- **Arduino Uno**
- **Ultrasonic Sensor**
- **Servo Motor**
- **Buzzer**
- **Pc to act as the raddar display**
- **Breadboard and jumper wires**

## Software Requirements
- **Arduino IDE**
- **Processing 4** 

## Circuit Diagram


## Setup Instructions
1. **Hardware Setup:**
   - **Ultrasonic Sensor:**
     - Connect VCC to 3.3V on the Arduino.
     - Connect GND to GND on the Arduino.
     - Connect the Data pin to digital pin 9 on the Arduino.
     - Connect the Data pin to digital pin 8 on the Arduino.
   - **Servo Motor**
     - connected to pin 10 on arduino
   - **Buzzer:**
     - Connect the green LED anode to digital pin 4 on an arduino Uno.

2. **Software Setup:**
   - Download and install the processing software:
   - Open the provided code file in the Arduino IDE.
   - Upload the code to the Arduino board.
   - Then set the corresponding ports on the processing software com13 and started the run.

## Usage
1. **Power the Arduino:**
   - Connect the Arduino to a power source (e.g., via USB or an external power supply).
   
2. **Monitor the Readings:**
   - Used the PC monitor to motor the range scan and red spots.
   
3. **Buzzer:**
   -used when a motion is sensed to area of range

