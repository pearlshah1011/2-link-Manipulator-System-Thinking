# Proportional-Integral-Derivative Controller for 2-Link Robotic Manipulator

## Abstract
This project delves into the implementation and examination of a Proportional-Integral-Derivative (PID) controller for a traditional 2-link robotic manipulator. It begins by outlining the equations governing the motion of the two-link robotic arm. The primary objective is to regulate the manipulator's movements to reach a specified position through computed torque control. MATLAB is utilized for control simulations, where the performance of the controller is assessed through various computer simulations. These simulations encompass Proportional-Derivative (PD), Proportional-Integral (PI), and PID control methods employing different sets of control parameters (kp, ki, kd). The efficacy of the controller is validated through MATLAB's SIMULINK. Furthermore, the strengths and limitations of each control model are scrutinized and discussed in detail.


## Contents
- Dynamics Formulation: Mathematical expressions delineating the dynamic behavior of the 2-link robotic arm, elucidating how its movements are governed.
- PID Controller Implementation: Application of the PID controller to regulate the position of the robotic manipulator, outlining the process of integrating proportional, integral, and derivative control components.
- Simulation Configuration: Elaborate guidelines on setting up simulations in MATLAB and SIMULINK, offering step-by-step instructions for executing the experiments.
- Findings and Interpretations: Examination of simulation outcomes and assessment of controller efficacy across different control paradigms, accompanied by insightful analysis.
- Prominent Utilization of SIMULINK: Emphasis on the pivotal role played by SIMULINK in visualizing and scrutinizing the simulated system, highlighting its significance in the study.
- Concluding Remarks: Summarization of key discoveries and perspectives gleaned from the investigation, encapsulating the implications of the study's outcomes.

## Pros and Cons of Different Control Models
- **PID Controller:**
  - *Pros:* Offers precise control over position, velocity, and acceleration. Relatively simple to implement.
  - *Cons:* Susceptible to oscillations and overshooting, requires tuning of multiple parameters.

- **PD Controller:**
  - *Pros:* Provides faster response than PID due to derivative action, reduces overshoot.
  - *Cons:* Unable to eliminate steady-state error, sensitive to noise and disturbances.

- **PI Controller:**
  - *Pros:* Eliminates steady-state error, suitable for systems with unknown disturbances.
  - *Cons:* Slower response compared to PD, may lead to oscillations in certain scenarios.
