auto_rollinghump_sim

This project is a simulation of autonomous rolling hump built on ODE (Open Dynamic Engine). 

* How it works:
MATLAB computes joint commands and send messages to the simulator through 'desiredAngles.txt'. The simulator reads joint commands and simulates for one step and send contact feedback to MATLAB.

* How to run:
(1) Start Matlab and set the workspace as: 'cd _CODE__DIR_/autoRollingHump';
(2) Open a terminal and 'cd _CODE__DIR_/autoRollingHump';
(3) Complile the simulator: make exampleViz
(4) Go back to Matlab and run 'RollingHump.m' in the folder '/kinematics';
(5) Then in terminal run: ./example

* Note:
It is recommended that MATLAB workspace should always be setted as '_CODE__DIR_/autoRollingHump'.

* Contact:
Weikun Zhen (zhenwk@gmail.com)
