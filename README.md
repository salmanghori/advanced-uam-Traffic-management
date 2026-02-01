# advanced-uam-Traffic-management

🚀 Project Overview
Note: The source code for this project is currently withheld pending formal publication. The visualization below demonstrates the simulation environment built in Godot Engine.

Simulation Scenario
This simulation visualizes high-density traffic in a high-rise urban environment. Key features include:

3D Intersections: Urban air taxis and drones navigating multi-lane corridors at varying altitudes.

Deconfliction: Automated traffic management at complex 3D junctions.

Control Architecture
The system utilizes a hybrid control strategy:

Autonomous Navigation: Agents operate on independent autonomous systems while in standard corridors.

Centralized Management (Control Zones): As agents enter the Control Zone (visualized as blue cuboids), authority shifts to a centralized controller.

Optimization: The centralized system uses Model Predictive Control (MPC) formulated as a Mixed-Integer Linear Programming (MILP) optimization problem to ensure safe and efficient deconfliction.

https://github.com/user-attachments/assets/5cf8f399-54c6-4851-939d-c844c89d0266

![compressed_simulation-ezgif com-optimize](https://github.com/user-attachments/assets/07097cbc-8b17-4653-9059-153bdd309557)


![UAM Trajectory Simulation](https://github.com/user-attachments/assets/07097cbc-8b17-4653-9059-153bdd309557)
