# 3D Scanner Project
## Project Resources

- [Project Documentation](https://drive.google.com/file/d/1EKke-tLkwMb0Dg1GsfDGWY0uqbY5y7aa/view?usp=sharing)
- [Project Presentation](https://docs.google.com/presentation/d/1XjHeJdVogjKGCzo6vBP9fqKM0ICfZaM6/edit?usp=sharing&ouid=101981796462723142981&rtpof=true&sd=true)
- ## Project Links

- [Project Video](https://drive.google.com/file/d/1T1wxv5Fxl5Pq1Qo0y-hY97qd-9RPsUp5/view?usp=sharing)
- [Prototype Model](https://drive.google.com/file/d/1oorwZ9qs8Y0QSyUMzn_1SrrFOqKO00aZ/view?usp=sharing)




## Problem Statement
The issue that encouraged the development of this 3D scanner system is the need for an affordable and efficient solution for 3D scanning applications in various industries such as engineering, architecture, and healthcare. Traditional 3D scanning technologies can be expensive and require specialized expertise, limiting their accessibility to smaller businesses and individuals. This system offers an accessible and customizable solution that can be built and operated by individuals with basic technical skills. The system's real-time scanning capabilities and high-resolution 3D modelling make it a valuable tool for industries that require accurate and detailed scans of complex shapes and geometries.

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




## Advantages:
Accuracy: 3D scanners capture objects with great precision.
Speed: Scanning is much faster than manual measurement.
Non-Contact: Scans without touching the object, ideal for fragile items.
Reverse Engineering: Helps recreate digital models from physical objects.
Customization: Used in custom manufacturing and prototyping.
Quality Control: Ensures products meet exact specifications.
Preservation: Helps digitize artifacts for record-keeping.
## Disadvantages:
Size Limits: Some scanners can only handle specific object sizes.
Lighting Issues: Scanners may not work well in poor lighting or with reflective objects.
Large Files: Scans create large data files that need lots of storage.
## Applications:
Manufacturing: Used for product design and inspection.
Healthcare: Scanning for prosthetics or dental work.
Architecture: Scanning buildings or objects for modeling.
Art and Preservation: Scanning artifacts for digital archives.
Education: Used in learning environments for research and projects.


- 📝 Check out my 

![IMAGE ](https://github.com/RAKESH-564/Email_Validator_project/blob/main/3d_image1.jpeg)

![IMAGE 2](https://github.com/RAKESH-564/Email_Validator_project/blob/main/3d_image2.jpeg)


