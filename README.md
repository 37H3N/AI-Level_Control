# AI-Enhanced PLC and Plant Systems Automation


https://github.com/37H3N/AI-Level_Control/assets/148967036/b40486f5-04b4-4fd0-854d-73ce47e7b601


![level-control](https://github.com/37H3N/AI-Level_Control/assets/148967036/f92ba11a-08b3-4f76-92d0-f5def17af896)

Project code in TIA Portal and model in FactoryIO.

## Table of Contents
- [Built With](#built-with)
- [About The Project](#about-the-project)
- [Features](#features)
- [Project Tree](#project-tree)
- [HMI Panel](#hmi-panel)
- [Controller](#controller)
- [How To Use](#how-to-use)
- [Factory IO](#factory-io)
- [TIA Portal](#tia-portal)
- [License](#license)

## Built With
- Factory I/O
- Siemens TIA Portal V17
- SIMATIC S7-PLCSIM
- GIT

## About The Project
This PLC program focuses on level control, with code developed in TIA Portal V17. The tank has been meticulously modeled in Factory IO's 3D simulation software.

The project includes a simple automation system featuring a liquid tank with two pumps and a liquid level sensor. The HMI allows users to select the controller type, configure its settings, and visualize its operation on a graph.

## Features
- **HMI Panel**
- **On-Off Controller**
- **PID Controller**
- **Takagi-Sugeno Fuzzy-PI Controller**
- **Neural Network NARX Controller**
- **Disturbance**

## Project Tree
The program is structured in four layers, resembling object-oriented programming concepts. Each layer is responsible for a specific task.

### HMI Panel
The HMI provides essential information about tank level control, displaying pump and sensor status, operating mode, controller selection, and a waveform graph. Users can modify default controller settings through the HMI.

### Controller
The program incorporates controllers written in SCL and LAD.

- **Ramp**: In automation systems, ramp functions serve as common input signals for controllers or actuators, facilitating smooth starts, stops, or speed regulation of mechanical systems.
- **On-Off**: An on-off controller with hysteresis, also known as a hysteresis controller, is a cost-effective control system turning the system on and off based on threshold values with added hysteresis to prevent rapid switching.
- **PID**: The incremental PID algorithm is a variant of the classic PID control algorithm, focusing on the change or increment in input rather than its absolute value.
- **TS (Takagi-Sugeno)**: The Takagi-Sugeno fuzzy PI controller adjusts proportional and integral gains based on current system conditions, using fuzzy logic.
- **NARX**: The NARX neural control system, based on a feedforward neural network, models and controls nonlinear dynamical systems.

## How To Use
Follow the PDF and ensure FactoryIO and TIA Portal (v16 and later) are installed on your computer.

# Future Development

As technology evolves and automation continues to play a pivotal role in the industrial revolution, this project has exciting possibilities for future development. The following are potential upgrades that can contribute to the advancement of automation and align with the trajectory of the industrial revolution:

## Enhanced Control Algorithms
Explore and implement advanced control algorithms such as Model Predictive Control (MPC), Adaptive Control, and Reinforcement Learning. These algorithms could provide more robust and adaptive control strategies, improving the system's performance and responsiveness to dynamic industrial environments.

## Integration of Industrial IoT
Incorporate Industrial Internet of Things (IIoT) capabilities to enable real-time monitoring, data analytics, and predictive maintenance. This integration could enhance the overall efficiency of the system by providing actionable insights and facilitating proactive maintenance, reducing downtime, and optimizing resource utilization.

## Cloud Connectivity
Implement cloud connectivity to enable remote monitoring and control. This upgrade would allow operators and engineers to access and manage the system from anywhere, promoting flexibility and scalability in industrial processes.

## Machine Learning for Anomaly Detection
Utilize machine learning techniques to develop anomaly detection systems. These systems could identify unusual patterns or behaviors in the industrial process, helping prevent faults, improve system reliability, and contribute to predictive maintenance strategies.

## Human-Machine Collaboration
Explore human-machine collaboration scenarios, integrating artificial intelligence to work alongside human operators. This collaborative approach could leverage the strengths of both humans and machines, fostering a more efficient and adaptive industrial ecosystem.

## Cybersecurity Measures
Enhance cybersecurity measures to ensure the integrity and confidentiality of industrial control systems. As automation becomes more interconnected, robust cybersecurity becomes paramount to protect against potential threats and vulnerabilities.

## Edge Computing
Investigate the implementation of edge computing for real-time processing and decision-making at the edge of the industrial network. This approach could reduce latency, improve system responsiveness, and optimize bandwidth usage in large-scale industrial environments.

## Sustainability Initiatives
Integrate sustainability initiatives into the control system, optimizing resource usage and minimizing environmental impact. This could involve developing energy-efficient control strategies, waste reduction measures, and environmentally conscious automation practices.

These future developments aim to propel the project into the forefront of technological innovation, contributing to the ongoing evolution of automation in the industrial landscape.

## License
Distributed under the MIT License. See LICENSE for more information.

