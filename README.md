# Sun Tracker

## Overview:

This project demonstrates a Sun Tracker system using Arduino and servo motors. The Sun Tracker is designed to orient a solar panel or solar collector towards the sun throughout the day, maximizing its energy harvesting efficiency. Light sensors are used to detect the sun's position, and servo motors adjust the orientation of the solar panel accordingly.

## Components:

1. Arduino Uno
2. Light sensors (LDRs)
3. Servo motors (2)
4. Solar panel or solar collector
5. Mounting hardware
6. Jumper wires
7. Power source (battery pack)

## Setup:

1. **Hardware:**
   - Mount the light sensors on a frame, ensuring they have a wide field of view of the sky.
   - Connect the light sensors to the Arduino according to the schematic.
   - Mount the servo motors to the solar panel frame or mount.
   - Connect the servo motors to the Arduino for control.

2. **Software:**
   - Download and install the Arduino IDE from [Arduino's official website](https://www.arduino.cc/en/software).
   - Open the Arduino IDE and create a new sketch.
   - Copy and paste the provided code into the sketch.
   - Save the sketch with an appropriate name.

## Click the image to watch the video demo:


<p align="center">
  <a href="https://github.com/sohailaesmat14/Sun_Tracker/assets/170406386/ad844a4d-95f2-45df-8708-93374eebdf71">
    <img src="https://github.com/sohailaesmat14/Sun_Tracker/assets/170406386/0ba6a6db-ee4c-49c2-8d30-891779b4f484" alt="Sun Tracker Project Demo" width="300"/>
  </a>
</p>

## Usage:

1. Upload the code to the Arduino board.
2. Place the Sun Tracker system outdoors in an open area with a clear view of the sky.
3. Power on the system.
4. The Sun Tracker should start adjusting the solar panel orientation to face the sun automatically.

## Notes:

- Ensure the light sensors have an unobstructed view of the sky to accurately detect the sun's position.
- Fine-tune the tracking algorithm parameters for optimal performance under different lighting conditions.
- Test the Sun Tracker system throughout the day to verify its effectiveness in tracking the sun's movement.
