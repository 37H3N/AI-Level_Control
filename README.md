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
To clone and run this application, ensure FactoryIO and TIA Portal (v16 and later) are installed on your computer.


