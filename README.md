# Proportional-Integral-Derivative (PID) Controller for 2-Link Robotic Manipulator

## Abstract
This paper proposes and analyzes a Proportional-Integral-Derivative (PID) controller for a classic 2-link robotic manipulator. Initially, we present the equations of motion for the two-link robotic manipulator. The primary focus is on controlling the robot manipulator to achieve the desired position using the computed torque control method. Control simulations are conducted using MATLAB, and various computer simulations are employed to evaluate the controller's performance. Specifically, simulations are performed under Proportional-Derivative (PD), Proportional-Integral (PI), and PID control with different sets of control gains (kp, ki, kd). The findings and analysis are verified through simulations using MATLAB's SIMULINK. Additionally, the pros and cons of different control models are discussed.


## Contents
- Equations of Motion: Mathematical equations describing the dynamics of the 2-link robotic manipulator.
- PID Controller Design: Implementation of the PID controller for controlling the manipulator's position.
- Simulation Setup: Detailed instructions on how to conduct simulations using MATLAB and SIMULINK.
- Results and Analysis: Discussion of simulation results and analysis of controller performance under different control models.
- Extensive Use of **SIMULINK**: Explanation of the significant role SIMULINK plays in visualizing and analyzing the simulated system.
- Conclusion: Summary of findings and insights gained from the study.

## Instructions for Simulations
1. Run the provided MATLAB scripts for PID controller design and simulation setup.
2. Adjust control gains (kp, ki, kd) as necessary to observe the effects on controller performance.
3. Utilize SIMULINK to visualize the simulated system and observe real-time responses.
4. Analyze the results and compare the performance of PD, PI, and PID control strategies.

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
