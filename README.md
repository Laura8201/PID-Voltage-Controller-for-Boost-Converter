# PID Voltage Controller for Boost Converter
MATLAB code developed to design and validate a PID voltage controller for a boost DC-DC converter stepping up from 24V to 48V. The controller was designed analytically in MATLAB, then implemented on a PCB with real components and tested in the lab.  
# What it does  
Models the boost converter transfer function in continuous conduction mode (CCM) and designs a type-3 compensator (2 zeros, 2 poles) to achieve a target bandwidth of 10 kHz and a phase margin of 50°. The code calculates the ideal resistor and capacitor values for the analog feedback network and verifies the result using real commercial component values.  
# Converter specs
Input voltage: 24V (±20%)  
Output voltage: 48V  
Switching frequency: 200 kHz  
Output power: 100W  
#How to run
Open the script in MATLAB and run it. It will plot the Bode diagrams of the open-loop converter, the PID compensator, and the closed-loop system, and print the calculated component values to the console.  
# Requirements
MATLAB with Control System Toolbox  
