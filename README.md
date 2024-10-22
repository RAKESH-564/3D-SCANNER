# 3D Scanner Project

## Overview
This project is a **3D Scanner** built using **Embedded C** and a variety of hardware components. It scans physical objects in 3D space, generating accurate digital models. The system is controlled using a **Joystick** and **Selection Button**, while a **Stepper Motor** drives the rotation platform. A **Camera** captures the object as it rotates, and results are displayed on an **LCD Screen**.

## Features
- 360-degree object scanning with stepper motor control.
- Data collection using a camera and sensor system.
- User interface with joystick and selection button.
- Live feedback and controls displayed on an LCD screen.
- Export scanned data to 3D model formats for further use.

## Hardware Components
- **Stepper Motor:** Controls the rotation of the object platform.
- **Joystick:** Used for user input and navigation.
- **Arduino Nano:** Microcontroller to control the system.
- **LCD Display:** Displays real-time information and scan progress.
- **Selection Button:** Used to start or stop the scanning process.
- **Camera:** Captures images of the object for scanning.
- **Motor Drivers:** Control the stepper motor for platform rotation.

## Software Components
- **Programming Language:** Embedded C.
- **IDE:** Arduino IDE or any compatible IDE.
- **Libraries:** Stepper motor control, LCD control, camera interface libraries.

## How It Works
1. **Rotation and Scanning:**
   - The object is placed on the rotating platform.
   - The platform rotates incrementally using the stepper motor, controlled via joystick inputs.
   - The camera captures the object at each step, creating a 3D model.

2. **User Interface:**
   - The LCD screen provides feedback during the scanning process.
   - The joystick allows users to navigate through the menu and start the scan.
   - The selection button is used to initiate the scan and control the scanning process.


├── src/               # Source code for the embedded system
├── docs/              # Documentation (circuit diagrams, explanations)
├── bin/               # Compiled binary files
├── README.md          # Project overview and instructions
└── LICENSE            # Licensing information (if applicable)

For a detailed explanation of the project, you can refer to the project presentation: 3D Scanner Project Presentation



```bash
git clone [https://github.com/RAKESH-564/3D-Scanner.git
cd 3D-Scanner]
