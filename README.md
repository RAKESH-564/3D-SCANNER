# 3D-SCANNER
# 3D Scanner Project

## Overview
This project is a **3D Scanner** built using **Embedded C** and various hardware components. It captures 3D models of objects using a **camera** and a **rotating platform**, controlled via a **joystick**. The **LCD display** provides real-time feedback, and a **selection button** is used to initiate and control the scanning process. The **stepper motor** rotates the platform, while **motor drivers** handle motor control. This project demonstrates expertise in embedded systems and hardware control.

## Features
- Real-time 3D scanning of objects using a camera.
- Stepper motor-driven rotational platform for full 360-degree object scans.
- Joystick for user input and controlling scanning parameters.
- LCD display for real-time feedback and status updates.
- Embedded C code handles motor control, sensor input, and data processing.

## Hardware Components
- **Microcontroller:** Arduino Nano.
- **Stepper Motor:** For rotating the scanning platform.
- **Joystick:** For controlling motor rotation and user input.
- **LCD Display:** 16x2 LCD for displaying scan status and data.
- **Selection Button:** To start/pause/stop the scanning process.
- **Camera:** For capturing object images to create a 3D model.
- **Motor Drivers:** (e.g., L298N) for controlling the stepper motor.
- **Power Supply:** 5V DC.

## Software Components
- **Language:** Embedded C (Arduino-based development).
- **IDE:** Arduino IDE.
- **Libraries:**
  - `Stepper.h` for motor control.
  - `LiquidCrystal.h` for LCD interface.
  - Custom camera libraries for interfacing with the camera.

## How It Works
1. **Object Placement:**
   - The object to be scanned is placed on the rotating platform.
   
2. **Joystick Control:**
   - The user controls the rotation angle and speed of the stepper motor using the joystick.
   
3. **LCD Display:**
   - The LCD provides real-time feedback on the scanning process, showing rotation angle, and scan status.
   
4. **Camera Capture:**
   - As the platform rotates, the camera captures multiple images from different angles to construct a 3D model.

5. **Motor and Camera Synchronization:**
   - The stepper motor rotates in small increments, with the camera capturing an image after each increment. The motor drivers control the motor’s precise movements.

6. **Selection Button:**
   - The user presses the button to start or stop the scanning process.


