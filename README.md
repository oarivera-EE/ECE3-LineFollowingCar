==========================================================================

Final Project for ECE3 - Line Following Car with Turnaround Detection

==========================================================================

Project Name: Autonomous Line-Following Car with TI-RSLK MAX

Description: This program controls a TI-RSLK MAX robot to follow a line using IR sensors and a PD-based control 

system. It detects intersections to perform turnarounds and uses timing constraints for navigation stability. 

Hardware Used:
- TI-RSLK MAX Robotics Kit
- MSP432 Microcontroller
- 8 Infrared (IR) Sensors for line detection

Features:
- PD control for smooth line-following
- Turnaround detection at endpoint and stop detection at starting point
 Adjustable speed and precision for stable navigation
 
Authors: Oscar Rivera, Andrew Cardona

Class: Introduction to Electrical Engineering (ECE 3) - Fall 2024

Notes:
- Ensure all connections to the TI-RSLK MAX are properly configured.
- Modify PID constants (Kp, Kd) to optimize performance on specific tracks.
- Modify built in timer function to ensure turnaround at desired point.
