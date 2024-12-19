# Prosthetic Movement Project

This repository showcases a comprehensive project designed to detect electromyography (EMG) signals and translate them into precise finger movements using a prosthetic hand. The implementation integrates machine learning algorithms for signal classification, Arduino for hardware control, and MATLAB for advanced data simulation and visualization.

## Project Overview

### 1. Machine Learning Module
The machine learning component processes EMG signals to predict prosthetic hand movements. A logistic regression model is employed to classify input signals, and predictions are relayed to an Arduino microcontroller to actuate servo motors. The module features a user-friendly graphical interface for real-time operation.

#### Key Features:
- Signal classification using a logistic regression model.
- Real-time predictions via an intuitive GUI.
- Communication with Arduino for hardware control.

### 2. Arduino Module
The Arduino module serves as the interface between the software and hardware, interpreting commands from the machine learning model to drive servo motors that control the prosthetic hand’s movements.

#### Key Features:
- Serial communication with the machine learning module.
- Reliable control of servo motors for accurate finger actuation.

### 3. MATLAB Module
The MATLAB component simulates the diffusion of signals in a spatial domain over time, offering insights into signal propagation and behavior. This module leverages finite element methods and provides a variety of visualization options.

#### Key Features:
- Advanced signal propagation simulations.
- Comprehensive visualization through 2D plots, 3D surface plots, and animations.

## How to Use

### Prerequisites:
- **Software:** Python (with `pandas`, `numpy`, `scikit-learn`, `tkinter`, and `pyserial`), Arduino IDE, and MATLAB.
- **Hardware:** Arduino microcontroller, servo motors, and supporting components.

### Steps:
1. **Setup:**
   - Install the required software and libraries.
   - Upload the Arduino sketch to the microcontroller.
   - Connect the hardware components as per the project requirements.

2. **Execution:**
   - Run the Python script to start the machine learning module and GUI.
   - Input EMG signal values through the GUI to predict movements and control the prosthetic hand.
   - Use MATLAB to simulate and visualize signal propagation dynamics.

## Contributions
This project represents a multidisciplinary effort, combining expertise in machine learning, hardware engineering, and computational simulations. The collaboration ensured the development of a robust system capable of accurately detecting and translating EMG signals into mechanical actions.

## License
This project is distributed under [specify license type], ensuring ethical use and contribution to the community.

## Acknowledgments
We extend our sincere gratitude to all contributors, mentors, and supporting organizations. This project benefited greatly from the resources and knowledge shared by open-source communities.

