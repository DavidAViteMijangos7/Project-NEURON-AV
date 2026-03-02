# Electronics Components
## Here I will list, describe and explain the connections of all the components

### Components that will be used:
* NVIDIA Jetson Orin Nano: The primary AI computer used for running ROS 2, performing SLAM, and processing real-time computer vision.
* **ESP32 DevKit V1:** The microcontroller that handles low-level tasks with the motors control, encoder reading, and Bluetooth/Wi-Fi connectivity.
* **RPLidar A1 M8:** A 360° laser scanner used for obstacle detection and generating 2D maps of the campus environment.
* **IMX219 Camera (CSI):** A high-definition camera module used for object recognition, traffic sign detection, and lane following.
* **BNO055 9-DOF IMU:** An intelligent 9-axis sensor that provides absolute orientation for precise navigation.
* **Hall Effect Encoders:** Sensors *integrated* into the motors to measure wheel rotation, allowing the system to calculate distance and speed.
* **JGB37-520 Geared Motors (12V):** High-torque DC motors with metal gearboxes designed to handle the weight of the AV.
* **L298N High-Current Motor Driver:** A H-bridge driver that regulates the power delivered to the 4-wheel drive system.
* **80mm High-Traction Wheels:** Rubber tires designed for optimal grip on concrete and asphalt surfaces.
* **3S LiPo Battery (11.1V / 5000mAh):** The main high-density power source for the system.
* **5V/5A Buck Converter:** A step-down voltage regulator that ensures a stable power supply for the Jetson Orin Nano and the LiDAR.
* **XT60 Connector & LiPo Alarm:** Safety and connectivity hardware used to monitor battery health and ensure secure power distribution.
