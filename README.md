# Two_wheel_self_balancing_Robot_simulations
MATLAB/Simulink-based control and simulation of a two-wheel self-balancing robot. Includes multibody modeling, state machine logic, PID tuning, Arduino deployment, and performance validation across four milestone challenges.
The project is divided into three milestones, each building upon the previous one to achieve simulation, control design, hardware deployment, and advanced robotic tasks.

🧩 Milestone 1 – Multi‑Body Simulation & Control Design

    • Built a Simscape Multibody model of an inverted pendulum and two‑wheel robot.
    • Defined base body and pendulum geometry with precise dimensions.
    • Applied actuation forces at the planar joint to study dynamic response.
    • Developed a state‑space representation and designed controllers.
    • Tuned gains for stability and upright equilibrium.
    • Validated results using Simulink Data Inspector.

🧩 Milestone 2 – State Machines & Hardware Integration

    • Implemented Stateflow charts for logic control (On/Off states, truth tables, superstates).
    • Added Simulink functions and time‑based triggers for periodic execution.
    • Exported code to Arduino IDE (MKR1000/MKR WiFi 1010).
    • Verified digital outputs with Blink test and ensured motor driver safety.
    • Integrated MecRoka S‑Function Library for IMU sensor data acquisition.
    • Modeled both virtual robot and physical robot with BLDC motor phase voltage conversion.
    • Designed a modular controller with task scheduling, IMU drivers, state estimation, and motor drivers.

🧩 Milestone 3 – Advanced Robot Challenges
Four major tasks were implemented and tested:
  1. 	3 meter Sprint

      • Robot drives 3 meters as fast as possible (~4 seconds).
      • PID controller tuned via frequency response method.
      • Velocity and pitch estimation validated in simulation and hardware.
  2. 	3 meter Sprint + Dual 360° Turns
     
      • Robot performs 360° turns at 1m and 2m marks.
      • Control logic deployed successfully (~13 seconds runtime).
      • Graphs confirm stability during linear and rotational transitions.
  3. 	Balancing with Additional Weight
     
      • Robot compensates for added load (~400g).
      • Position‑based control with PID tuning (Ziegler–Nichols method).
      • Stable up to 400g; instability observed beyond this threshold.
  4. 	Figure 8 Path (Two Circles, 1m Diameter Each)
     
      • Robot executes a closed‑loop figure 8 trajectory (~19 seconds).
      • Smooth transitions between anti‑clockwise and clockwise semicircles.
      • Graphs confirm stable velocity and yaw control.

📊 Key Features

    • MATLAB/Simulink models for simulation and control.
    • Stateflow charts for autonomous task execution.
    • PID tuning methods (Frequency Response, Ziegler–Nichols).
    • Hardware deployment on Arduino MKR boards.
    • IMU integration for real‑time sensor feedback.
    • Performance validation with graphs and video demonstrations.


🚀 Two-Wheel Robot Control & Simulation (Milestones 1–3)
📖 Overview
This repository documents the step‑by‑step development of a two‑wheel self‑balancing robot using MATLAB/Simulink and embedded hardware integration.
The work was carried out as part of the M.Sc. Mechatronics Engineering program at Hochschule Kaiserslautern under the course System Level Rapid Development in Mechatronics (WS 2023/24).
The project is divided into three milestones, each building upon the previous one to achieve simulation, control design, hardware deployment, and advanced robotic tasks.

🎥 Demonstrations
- Challenge 1 – 3m Sprint
- Challenge 2 – Sprint + 360° Turns
- Challenge 3 – Balancing with Weight
- Challenge 4 – Figure 8 Path
  
🚀 **Videos links are available in the report "Milestone_3 _Robot_Challenges.pdf"**

