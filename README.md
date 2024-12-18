# NMOS-TCAD-Simulation
## Overview
This project focuses on designing and simulating an N-channel MOSFET (NMOS) transistor using Sentaurus TCAD tools. The simulations explore the effects of substrate doping concentration and applied voltages on critical device parameters, including:

Threshold Voltage (Vt)
Subthreshold Slope (SS)
Transconductance (gm)
Punch-through behavior at high drain-to-source voltages.
The project demonstrates the use of SDE, SDevice, and SVisual tools for structure definition, electrical simulation, and visualization, respectively.

## Features
Device Design: Define NMOS geometry and doping profiles in SDE.
Electrical Simulation: Analyze I-V curves, threshold voltage, and punch-through conditions using SDevice.
Result Visualization: Generate band diagrams, electron density profiles, and electrostatic potential maps in SVisual.

## Directory Structure

NMOS_Transistor_Simulation_TCAD/
├── sde/                  # SDE input files for device geometry and doping
├── sdevice/              # SDevice input files for electrical simulations
├── svisual/              # SVisual configuration and output files
├── report/               # Final project report and additional documentation
├── LICENSE               # License file (optional)
└── README.md             # Project description and usage guide

##  Prerequisites
Sentaurus TCAD: Licensed software including SDE, SDevice, and SVisual.
A computer capable of running intensive simulations.
Basic knowledge of semiconductor physics and MOSFET operation.


## How to Use
1. Structure Definition (SDE)
Open the files in the sde/ directory using Sentaurus Structure Editor.
Modify parameters like doping concentration or geometry as needed.
Save the output for use in the simulation step.
2. Simulation (SDevice)
Load the files in the sdevice/ directory using Sentaurus Device.
Run the simulations to generate I-V curves, band diagrams, and other outputs.
Analyze results using the configured settings.
3. Visualization (SVisual)
Use the files in the svisual/ directory to view simulation results.
Generate graphs like electron density profiles and band diagrams.
4. Report
Refer to the report/ directory for the detailed PDF report of the project findings.

## Key Results
1. I-V Characteristics
Drain current (ID) as a function of gate voltage (VG) for different doping concentrations.
Threshold voltage shifts with varying doping profiles.
2. Band Diagrams
Visualization of band energy levels at different gate and drain voltages.
3. Punch-through Analysis
Effects of high drain-to-source voltage on carrier flow and depletion regions.
Files Description
sde/: Contains all input files required to define the device structure.
sdevice/: Input files for running simulations on the defined NMOS structure.
svisual/: Files for configuring visualization and analyzing results.
report/: Includes the detailed final report in PDF format summarizing all observations.
Graphs and Visuals
Key visuals from the simulations include:

ID vs. VG curves: Analyzing threshold voltage and drive current.
Band diagrams: Showing energy bands for different doping levels.
Electron density profiles: Highlighting conduction regions.
References
Sentaurus TCAD Documentation
Lab instructions from EE303 course at Minnesota State University, Mankato.
Research paper references included in the final report.
License
This project is for educational and academic purposes. Please contact the author for permission if you intend to use the files for commercial applications.
