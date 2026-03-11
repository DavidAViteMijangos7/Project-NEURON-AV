# My own logbook into my engineering carrer.
NEURON AV (utonomous Vehicle) Porject
## 02/26/2026 The start of my project
This is the first day of my AV project. The main reason for this project is for tunning my mechanical, electrical and programming skills I am learning as a fourth semster engineering student.
As I will be working almost everyday on this project, during my freetime and study time I will document every step I take for everyone that is looking for a pathway to learn many skills in a short time in order to make a project of their own interest.

###**Starting this project this is a list of my actual skills starting the project:**
 1. In terms of CAD I am currently working on my CSWA certification on SolidWorks and I have like 1-2 months of experience in this software.
 2. I am currently learning the basics in mechatronics in my carrer.
 3. I have done some small arduino circuits that I will upload in another repository, just to get used to the interface and programming, along with the use of plenty of components.
 4. Currently I have basic/intermediate knoweledge in some programming languages like Python, R, C++, and Matlab (my favorite for now).
 6. I have planned the first steps for this projects and started my GitHub page with the help of an AI as a introductory guide for GitHub.
 7. I have done some basic work with fusion360 and some CSWA and CSWP level pieces in SolidWorks.
 8. I have some knowledge in real world kart and mechanical construction due to some student groups.

#### Next Steps
For the next days I will be working on choosing the components, even though I have been working witth arduino, this proyect is far more complex than a simple arduino code, so I will research on my own with the use of internet, youtube and AI; with the objective to choose the best components for this proyect.
After this main research I will be working on my car's master sketch in SolidWorks.
I will try to get a full first draft design of the car by the end of the next 2 weeks along with finishing my preparation for the CSWA certification.

## 03/01/2026 Defining component to start the first CAD design
During this couple day i have researched the components I will need for my proyect to autonomously work.
- I will need the main cameras and sensors that will look out for people and obstacles, for this proyect it is important that the AV has awarness of a 360 degree view of its surroundings and with this, a camera that is able to identify any obstacle, due to this I have decided to try and use the **RPLidar A1**	for the 360 surroundings scanning with a **IMX219** camera for obstacles identification. A **BNO055** will be used to control the direction and stabilize the AV in case of any non even terrain or crack.
- To control, decode and process the AI and executes the map/SLAM of the campus and autonomously control the car I need a powerful processor to run everything at the same time, for this I will be using the **NVIDIA Jetson Orin Nano** wich has enough processing power for everything and is compatible with all the components.
- For the car movement I will be using 4 **JGB37-520** motors, 1 conncected to each of the wheels and all of them controlled by an **ESP32** connected to the Jetson Orin and passing through a **L298N** to control the power, also via WiFI/Bluetooth I can make a direct connection with the ESP32, or create a full connection wit the Jetson to be able to see the cameras too.
- Finally to power the whole system I will use **LiPo 3S lithium batteries**, providing 11.1V of power between the 3, this power will be distributed by a **XT60** conector and a step-down for the Jetson.
  
**All this components will be uploades in the /electronic file**
**The volume measures and mass from each component will be noted in the /mechanics file where I will describe the start of the whole AV first design**

## 03/10/2026 Advances and next steps
The last week I have been working on the main CAD design and I have completed my first design of the AV, it will be a small car which main purpose is to make the software work and work with it until the interface is 100% functional and works on campus, I have also uploaded new things on both the mechanical and electronics carpets, from the designs downloaded from the component, to the parameters, weights and other imporant considerations for choosing the motors and the system.
Summary:
* Updated the mechanical implications on the mechanical/ and the specifications of the componenets on the electrical/
* Completed the first CAD of the AV, ready for 3D printing.
Next Steps:
* Due to the fact that I currently do not have the main components or the motors, I will start working on the interface that will be reading the environment and the program that will be uploaded to the microcontroller and the Jetson Orin.
* Upload the remaining files and calculations on the mechanical and electrical parts, on the mechanical side,, the first CAD with the components, on the electrical, the order of the components, how will they be connected.
