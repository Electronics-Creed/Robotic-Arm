# Robotic-Arm

In this project we deal with the design and control of a robotic arm with 3 degrees of freedom. Our model has been constructed using four links and three revolute joints. Two types of grippers have been designed, a mechanical gripper and an electromagnetic gripper. A simulation of the robotic arm is done to visualize the joint movements using Robotics Toolbox for MATLAB whichis also covered in detail. We generate a well-defined set of trajectory points for motion planning of the simulated model. The hardware implementation is achieved using Arduino Uno which is controlled by a Simulink model. This is a ReadMe template to help save you time and effort. 

---

### Table of Contents
You're sections headers will be used to reference location of destination.

- [Installation](#installation)
- [Technologies](#technologies)
- [How To Use](#how-to-use)
- [Other links](#other-links)
- [References](#references)
- [Author Info](#author-info)

---

## Installation

- Install the robotics toolbox package by Peter Corke using this link: 
    > https://petercorke.com/toolboxes/robotics-toolbox/

- Install the Simulink support packacge for Arduino using this link: 
    > https://in.mathworks.com/matlabcentral/fileexchange/40312-simulink-support-package-for-arduino-hardware

---

## Technologies

- Arduino
- MATLAB
- Simulink

---

## How To Use

#### Simulation
Run the simulaiton.mlx file section by section in MATLAB to visualize the motion of the robotic arm which is created using the robotics toolbox. In the first and second section we create the robot model and initialize necessary parameters. In the third section we move the robot arm to a given point and in the fourth section we move the robotic arm through given set of waypoints. In the subsequent section some funtions have been defined.

#### Hardware
The files used for hardware implementation are hardware_implementation1.slx and hardware_implementation2.slx. The file hardware_implementation1.slx is used to move the robot arm to a given point and activate the gripper. The second file is used to move the robotic arm through given set of waypoints and activate the gripper at the required points. Refer the circuit diagram for the connections to Arduino.

---

## Other links

Drive link: 
 > https://drive.google.com/drive/folders/1rfMxBnnn4IuiM7Yzvbfr_llIJidcPY3G?usp=sharing

Youtube playlist
 > https://www.youtube.com/playlist?list=PLSWRiv_s7diOQ1Fk6TX-yL9LCNg870Yoa

---

## References

Robotics toolbox, MATLAB robotics toolbox by Peter Corke
 > https://www.petercorke.com/RTB/r9/html/SerialLink.html

Simulink Support Package for Arduino Hardware User’s Guide, Mathworks
 > https://in.mathworks.com/help/pdf_doc/supportpkg/arduino/arduino_ug.pdf

3 Axis Robotic Arm , Abhivyakti Sharma, Kshitija Kanase, Vipul Pandey, C. K. Bhange
 > https://www.ijresm.com/Vol.2_2019/Vol2_Iss6_June19/IJRESM_V2_I6_25.pdf

---

## Author Info

- H P Jeevan
- G Rohith
- Emyl Varghese George
