# Project-NEURON-AV
Development of a scale autonomous vehicle for campus navigation. Includes advanced mechanical design in SolidWorks (CSWA/CSWP standards), electronic architecture with NVIDIA Jetson Nano, and control systems based on ROS 2.
# Campus Autonomous Navigator (CAN) 🏎️🤖

### Mechatronics Engineering Project: Scale Autonomous Vehicle

This project involves the design, modeling, and programming of an autonomous vehicle capable of navigating pedestrian environments (university campus). The primary focus is the integration of high-precision mechanical design with Artificial Intelligence perception systems.

---

## 1. Mechanical Design (SolidWorks) 🛠️
The chassis and steering systems were developed following **CSWA/CSWP** certification standards, prioritizing design intent and manufacturing optimization (3D Printing and laser cutting).

* **Parametric Design:** Implementation of a *Master Sketch* for global dimensional control.
* **Mass Analysis:** Optimization of the center of gravity to ensure stability during cornering.
* **Configurations:** Adaptable models for outdoor tires (Campus) and omnidirectional wheels (Indoors).

## 2. Electronic Architecture and Perception 🧠
The system utilizes a hierarchical architecture for real-time processing:
* **Main Processor:** NVIDIA Jetson Nano (Vision processing and AI).
* **Perception:** 2D LiDAR for SLAM mapping and a camera for lane detection.
* **Motor Control:** ESP32/Arduino managing odometry via encoders.

## 3. Software 💻
* **Stack:** ROS 2 (Humble), Python, OpenCV.
* **Algorithms:** SLAM implementation for map generation and autonomous navigation through *Path Planning*.

---

## Repository Structure
- `/mechanical`: CAD Files (.SLDASM, .STEP) and renders.
- `/software`: Navigation and control source code.
- `/electronics`: Circuit diagrams and Bill of Materials (BOM).

## About the Author
**David Andre Vite Mijangos** Mechatronics Engineering Student at Tecnológico de Monterrey.  
*Interests: Automotive, Aerospace, and Consulting Industries.*
