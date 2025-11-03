# 🗺️ Qu Robotics Team — Learning Roadmap

> “Before we build robots that think, we must think like engineers.”

This roadmap guides new members through the **core knowledge** required to become fully capable contributors in the Qu Robotics Team.  
It’s divided into **phases** — each focusing on building a layer of understanding essential for robotics development.

---
## Phase 1 — Mathematical Fundamentals 

| **Subject** | **Best Free Resources** | **Main Tools** | **Used In** |
|--------------|--------------------------|----------------|--------------|
| **Linear Algebra** | - [3Blue1Brown: Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) <br> - [MIT 18.06 Linear Algebra (Gilbert Strang)](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/) | [**-MATLAB Onramp** ](https://matlabacademy.mathworks.com/details/matlab-onramp/gettingstarted) <br> [**-Linear Algebra in MATLAB and Python(NumPy)** ](https://github.com/mikexcohen/LinAlgBook)| - State-space modeling <br> - Robot kinematics <br> - Control stability (eigenvalue analysis) |
| **Calculus** | - [3Blue1Brown: Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) <br> - [Khan Academy: Calculus 1 & 2](https://www.khanacademy.org/math/calculus-1) | [**-MATLAB Symbolic Toolbox**](https://github.com/MathWorks-Teaching-Resources/Calculus-Derivatives) <br> [ **-Python (SymPy)** ](https://youtu.be/VDFRpjQVaME?si=r5WBjRgSzSWBshxH)| - System dynamics <br> - Control law design <br> - Modeling continuous-time systems |
| **Geometric Functions** | - [Khan Academy: Trigonometry Course](https://www.khanacademy.org/math/trigonometry) <br> - [3Blue1Brown: Essence of Trigonometry](https://www.youtube.com/results?search_query=essence+of+trigonometry+3blue1brown) | - **MATLAB** <br> - **Python (Matplotlib + NumPy)** | - Robot motion and rotations <br> - Drone attitude control <br> - Coordinate transformations |
| **Probability Theory** | - [MIT 6.041 Probabilistic Systems Analysis](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-041sc-probabilistic-systems-analysis-and-applied-probability-fall-2013/) <br> - [StatQuest: Probability & Bayes Theorem](https://www.youtube.com/user/joshstarmer) | - **Python (NumPy, SciPy, Matplotlib)** | - Sensor noise modeling <br> - Kalman filtering <br> - Uncertainty estimation in robotics |
| **Pseudo-Code & Algorithms** | - [NPTEL: Design and Analysis of Algorithms](https://nptel.ac.in/courses/106/105/106105164/) <br> - [YouTube: How to Read and Write Pseudocode (Computer Science Tutor)](https://www.youtube.com/results?search_query=how+to+read+and+write+pseudocode) | - **Python (Jupyter Notebook or VS Code)** | - Control algorithms (PID, LQR) <br> - Path planning <br> - System simulations |
---
## Phase 2 — Basic Electronics  

| **Subject** | **Best Free Resources** | **Main Tools** | **Used In** |
|--------------|--------------------------|----------------|--------------|
| **Electric Circuits Fundamentals** | - [All About Circuits: DC/AC Fundamentals](https://www.allaboutcircuits.com/textbook/) <br> - [Khan Academy: Intro to Circuits](https://www.khanacademy.org/science/electrical-engineering/ee-circuit-analysis) <br> - [Instructables: Basic Electronics Projects](https://www.instructables.com/Basic-Electronics/) | - **Multisim Live** <br> - **Tinkercad Circuits** | - Power distribution in robots <br> - Sensor and actuator interfacing <br> - Battery management |
| **Ohm’s Law & Kirchhoff’s Laws** | - [The Organic Chemistry Tutor: Circuit Analysis Tutorials (YouTube)](https://www.youtube.com/playlist?list=PL0o_zxa4K1BVsziIRdfv4Hl4UIqDZdI6K) <br> - [Electronics Tutorials: KVL & KCL](https://www.electronics-tutorials.ws/dccircuits/dcp_4.html) <br> - [Electronics Tutorials Main Site](https://www.electronics-tutorials.ws/) | - **CircuitLab** <br> - **LTSpice** | - Analyzing voltage/current in robot components <br> - PCB circuit debugging |
| **Electronic Components** *(Resistors, Capacitors, Diodes, Transistors)* | - [Afrotechmods: Basic Components Explained (YouTube)](https://www.youtube.com/@Afrotechmods) <br> - [SparkFun: Components Reference Guide](https://learn.sparkfun.com/) <br> - [Instructables: Component-Based Projects](https://www.instructables.com/Basic-Electronics/) | - **Breadboard + Multimeter** <br> - **Proteus Simulation** | - Motor drivers <br> - Sensor circuits <br> - Power regulation |
| **Sensors & Actuators** | - [Introduction to Sensors (NPTEL)](https://nptel.ac.in/courses/108105064) <br> - [SparkFun Sensors Guide](https://learn.sparkfun.com/tutorials/sensors/all) <br> - [DroneBot Workshop: Actuators & Motors](https://dronebotworkshop.com/) | - **Arduino IDE** <br> - **Raspberry Pi GPIO** | - Obstacle detection <br> - Motion control <br> - Feedback systems |
| **Analog vs Digital Electronics** | - [Electronics Tutorials: Analog vs Digital](https://www.electronics-tutorials.ws/digital/dig_1.html) <br> - [Khan Academy: Logic Gates](https://www.khanacademy.org/computing/computer-science/cryptography/digital-information/a/logic-gates) | - **Logic.ly** <br> - **Proteus Logic Analyzer** | - Interfacing microcontrollers <br> - Signal conditioning <br> - Embedded control |
| **Measurement & Testing** | - [EEVblog: Multimeter & Oscilloscope Basics](https://www.youtube.com/user/EEVblog) <br> - [Electronics Tutorials: Measuring Instruments](https://www.electronics-tutorials.ws/) | - **Multimeter** <br> - **Oscilloscope (Virtual or Real)** | - Circuit troubleshooting <br> - Performance analysis <br> - Sensor calibration |
| **PCB Design & Fabrication**  | - [EEVblog: PCB Design Tutorials](https://www.youtube.com/@EEVblog) <br> - [Altium Academy: PCB Layout Series](https://www.youtube.com/@AltiumAcademy) <br> - [KiCad Official Docs](https://docs.kicad.org/) <br> - [MIT OpenCourseWare: Electronics Design](https://ocw.mit.edu/) <br> - [Electronics Globe: PCB design using Ki-CAD](https://youtube.com/playlist?list=PLkEZIY-NgCD_tuHk_gR0RWVecNoOZ157G&si=olkp6XjLs_Vv0hOp) | - **KiCad (Free/Open Source)** <br> - **EasyEDA** <br> - **Fusion 360 Electronics** | - Professional PCB design for sensor and motor driver circuits <br> - Power regulation and signal integrity design <br> - Control board development |


---
## Phase 3 — Basic of Microcontrollers 



---
## Phase 4 — Mechanics and Design  

### General Overview

**Focus:** Applied Mechanics, CAD, and Manufacturing

This phase introduces physics-based simulation (e.g., using Gazebo or CoppeliaSim), static and dynamic analysis, and professional CAD software such as SolidWorks, Inventor, or Fusion 360.

### Objectives

- Understand the physics governing robotic movement and structure (kinematics and dynamics introduced practically here; formalized in Section 6).  
- Select appropriate materials and components based on quantitative requirements (stress, strain, weight, cost).  
- Develop proficiency in Computer-Aided Design (CAD) for prototyping and manufacturing.  
- Translate a conceptual design into a physical, functional prototype.  

---

| **Subject** | **Best Free Resources** | **Main Tools** | **Used In** |
|--------------|--------------------------|----------------|--------------|
| **Engineering Design Process & Applied Mechanics** | [MIT OpenCourseWare – Mechanics & Dynamics](https://ocw.mit.edu), NASA Robotics Design Guide | SolidWorks / Fusion 360, MATLAB (for calculations) | Designing robot drive trains, defining specifications under constraints |
| **Applied Statics & Free Body Diagrams (FBDs)** | *Vector Mechanics for Engineers* textbook, Khan Academy (Statics), NASA Design Guide | CAD + Physics Sim (Gazebo / CoppeliaSim) | Force and torque analysis, stability checks before CAD modeling |
| **Applied Dynamics** | MIT OCW Dynamics Lectures, *Vector Mechanics for Engineers (Dynamics)* | MATLAB, Fusion 360 Simulation | Center of gravity, friction, and stability calculations |
| **Material Science & Selection** | McMaster-Carr Catalogs, *Machinery’s Handbook*, NASA Robotics Design Guide | Fusion 360, Datasheet references | Choosing materials (Al 6061, ABS, Delrin, PEEK) based on mechanical properties |
| **Computer-Aided Design (CAD) Mastery** | Autodesk Education (Fusion 360 Free License), SolidWorks Student Edition | SolidWorks / Fusion 360 / Inventor | Parametric modeling and assembly creation |
| **Engineering Drawings & DfM (Design for Manufacturing)** | YouTube: “Learn SolidWorks Drawings”, *Machinery’s Handbook* | SolidWorks Drawing Module / Fusion 360 Technical Drawing | Creating manufacturing-ready blueprints and BOMs |
| **Finite Element Analysis (FEA)** | *SolidWorks Simulation Tutorials*, *Fusion 360 Stress Analysis Guides* | FEA within SolidWorks or Fusion 360 | Predicting stress, strain, and failure points virtually |
| **Gears, Belts, and Power Transmission** | SDP/SI Catalogs, MIT OCW: Mechanisms & Gear Theory | Fusion 360 Motion Study, SolidWorks Motion | Designing reduction systems and power trains |
| **Linkage Design & Actuation** | CoppeliaSim Tutorials, YouTube: “Linkage Simulation in CAD” | Fusion 360 Motion Study, Gazebo | Simulating 4-bar and 5-bar linkages, motor and actuator testing |
| **Manufacturing & Prototyping Techniques** | *Fusion 360 CAM Tutorials*, University Machine Shop Guides | CNC, Laser Cutter, 3D Printer (FDM/SLA) | Fabricating robot parts from CAD models |
| **Hands-On Prototyping & Validation** | YouTube: “Destructive Testing Basics”, *NASA Robotics Testing Procedures* | Load-testing rigs, sensors | Testing parts under load, comparing simulation to real-world results |
| **Soldering & PCB Assembly (Optional for Integration)** | EEVblog Soldering Tutorials, SparkFun Soldering Guide | Soldering Iron (60W+), Flux, Multimeter | PCB assembly for control electronics or sensor integration |

---

## Recommended Resources

| **Type** | **Resource Name** | **Description** |
|-----------|------------------|-----------------|
| **Software** | **SolidWorks** | Industry-standard CAD software for professional design and simulation. |
| **Software** | **Gazebo** | Open-source physics-based simulator for robotics applications. |
| **Software** | **CoppeliaSim** | Physics-based robotic simulator supporting dynamic analysis. |
| **Software** | **Autodesk Fusion 360** | Free for students; integrates CAD, CAM, and FEA. |
| **Textbook** | *Vector Mechanics for Engineers (Statics/Dynamics)* | Standard university reference for mechanical fundamentals. |
| **Textbook** | *Machinery’s Handbook* | Authoritative guide on physical design and manufacturing. |
| **Reference** | **NASA Robotics Design Guide** | Practical design and testing examples from real robotics applications. |
| **Reference** | **McMaster-Carr / SDP-SI Catalogs** | Real-world material and component datasheets. |
| **Online Learning** | **MIT OpenCourseWare** | Free engineering course materials on mechanics, dynamics, and CAD. |
| **Facilities** | **University Makerspace / Lab** | Access to 3D printers, laser cutters, and CNC machines is mandatory. |

---

### Suggested Projets 

**Mini Project:**  
Design and fabricate a small robotic arm or drive train.  
- Define requirements (weight, torque, motion range).  
- Design in Fusion 360 or SolidWorks.  
- Simulate with CoppeliaSim or Gazebo.  
- Fabricate components via 3D printing and laser cutting.  
- Validate results through stress testing and center-of-gravity analysis.

---

## Phase 5 — Sensors and Actuators  



---

## Phase 6 — Control Systems, Kinematics, and Dynamics 

---

### General Overview

This section formalizes the mathematics and theory introduced practically in earlier modules.  
It covers the core principles of **robot control**, **movement planning**, and **system dynamics**.  
Participants will develop mathematical models for robotic systems and implement **closed-loop feedback control** using industry-standard tools and simulation environments.

---

### Objectives

- Derive and implement **forward and inverse kinematics** for robotic manipulators and mobile bases.  
- Understand and tune **feedback mechanisms**, primarily **Proportional-Integral-Derivative (PID)** controllers.  
- Model robotic system dynamics using **Newton-Euler** or **Lagrangian mechanics**.  
- Utilize advanced **simulation and control environments** (MATLAB/Simulink, ROS/Gazebo).  

---

| **Subject** | **Best Free Resources** | **Main Tools** | **Used In** |
|--------------|--------------------------|----------------|--------------|
| **Open-Loop vs. Closed-Loop Control Systems** | MIT OCW: *Dynamics & Controls*, YouTube: *Control Systems Basics* | MATLAB/Simulink, Arduino IDE, Python | Comparing open-loop vs. closed-loop motor control with encoder feedback |
| **PID Control Theory** | *Modern Control Engineering* by Katsuhiko Ogata, MATLAB Control Tutorials | MATLAB/Simulink, CoppeliaSim | Tuning P, I, D gains to minimize steady-state error and overshoot |
| **Stability Analysis** | MATLAB System Identification Toolbox Guides, MIT OCW *2.004 Controls* | MATLAB, Python (control library) | Measuring overshoot, settling time, and verifying system stability |
| **Forward Kinematics** | *Robotics: Modelling, Planning and Control* by Bruno Siciliano, YouTube: *Intro to Kinematics* | Python / C++, MATLAB | Computing end-effector position/orientation from joint angles |
| **Inverse Kinematics** | Stanford Robotics Lectures, CoppeliaSim Tutorials | Python / C++, ROS, Gazebo | Solving for joint angles to reach a specific target position |
| **Homogeneous Transformation Matrices (HTMs) & D-H Parameters** | MIT OCW *Introduction to Robotics*, ROS Wiki | MATLAB, Python (NumPy, SymPy) | Modeling robotic manipulators and verifying link transformations |
| **System Dynamics (Newton-Euler, Lagrangian)** | MIT 2.004 Dynamics and Controls, YouTube: *Robot Dynamics Basics* | MATLAB/Simulink, Python | Deriving equations of motion for arms, pendulums, or mobile bases |
| **Actuator Dynamics** | Motor datasheets (e.g., Maxon, Pololu), *Modern Control Engineering* | MATLAB, ROS, CoppeliaSim | Simulating torque, inertia, and acceleration limits |
| **Trajectory Planning** | Python Robotics (GitHub), Coursera: *Robot Motion Planning* | Python, MATLAB | Implementing smooth polynomial trajectories for motion control |
| **ROS Control Stack (ros_control, URDF)** | [ROS Wiki: ros_control](https://wiki.ros.org/ros_control), *Gazebo Tutorials* | ROS, Gazebo, URDF/Xacro | Defining joints, actuators, and controllers in a simulation environment |
| **Integration of Control Loops** | ROS2 Control Tutorials, YouTube: *Gazebo Control Integration* | ROS, Gazebo, MATLAB/Simulink | Building a full closed-loop control system using inverse kinematics |
| **Simulation Validation** | CoppeliaSim, Gazebo, MATLAB Simscape | MATLAB/Simulink, ROS/Gazebo | Testing controller performance and verifying kinematic/dynamic accuracy |

---

### Recommended Resources

| **Type** | **Resource Name** | **Description** |
|-----------|------------------|-----------------|
| **Software** | **MATLAB/Simulink** | Industry-standard tool for control system design, simulation, and analysis. |
| **Software** | **ROS (Robot Operating System) + Gazebo** | The primary framework for modern robotics research and control simulation. |
| **Software** | **Python / C++** | Core programming languages for control implementation in both real and simulated systems. |
| **Textbook** | *Robotics: Modelling, Planning and Control* — Bruno Siciliano | Comprehensive reference for kinematics, dynamics, and control. |
| **Textbook** | *Modern Control Engineering* — Katsuhiko Ogata | Classic control theory resource (PID, stability, frequency response). |
| **Online Course** | *MIT 2.004 Dynamics and Controls* | Free MIT OCW course on system dynamics and control theory. |
| **Reference** | *ROS Wiki – ros_control & URDF* | Official reference for defining and managing control interfaces in ROS. |

---

### Suggested Projects

**Mini Project:**  
Design and simulate a **2-DoF robotic arm** in **ROS + Gazebo** or **CoppeliaSim**, implementing a complete feedback control loop.

**Steps:**
1. Derive forward and inverse kinematics using D-H parameters.  
2. Implement a PID controller for each joint.  
3. Generate smooth motion trajectories between waypoints.  
4. Simulate motion in Gazebo with realistic physics.  
5. Plot response metrics (overshoot, steady-state error) and tune gains.  

---



---
> © All Rights Reserved — Qu Robotics Team 2025

