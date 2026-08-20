Project Overview

This project presents a process simulation of hydrogen production from methane by partial oxidation using DWSIM, an open-source process simulation software.
The objective of the project is to develop and analyze a simulated process for producing hydrogen from methane and to study the behavior of the process under specified operating conditions.

Process Description

Partial oxidation of methane is a hydrogen-production route in which methane reacts with a limited amount of oxygen to produce hydrogen and carbon monoxide.
The main reaction considered is:
CH₄ + ½O₂ → CO + 2H₂
The process is exothermic and can operate without the external heat input required by conventional steam reforming.

Software Used
DWSIM – Process simulation and flowsheet development
Microsoft Excel – Optional processing and analysis of simulation results

Simulation Approach
The process was developed in DWSIM by defining the required chemical components, thermodynamic properties, feed conditions, reaction system, and process streams.
The general simulation workflow consists of:

Defining the chemical components.
Selecting an appropriate thermodynamic/property package.
Defining methane and oxygen feed streams.
Specifying the feed operating conditions.
Defining the partial oxidation reaction.
Simulating the reactor.
Analyzing the outlet stream composition and hydrogen production.
Evaluating the effect of operating conditions on the process.

Process Flowsheet

The DWSIM flowsheet represents the conversion of methane and oxygen into hydrogen-rich product gas through the partial oxidation reaction.

The complete DWSIM simulation file is provided in this repository:

HYDROGEN PRODUCTION BY METHANE.dwxmz

The file can be opened using DWSIM to inspect the flowsheet, streams, reactor configuration, and simulation parameters.

Key Engineering Parameters

The simulation can be evaluated using parameters such as:

Methane conversion
Hydrogen production
Hydrogen mole fraction
Carbon monoxide formation
Oxygen consumption
Feed and product flow rates
Reactor temperature
Reactor pressure
Heat duty, where applicable
Results

The simulation results are obtained from the DWSIM model and can be used to evaluate the performance of the methane partial oxidation process.

Important performance indicators include:
Parameter	Result
Methane conversion	Obtained from DWSIM
Hydrogen production	Obtained from DWSIM
Hydrogen mole fraction	Obtained from DWSIM

The simulation provides practical exposure to:
Material balance
Reaction engineering
Thermodynamic property selection
Process flowsheet development
Reactor simulation
Stream analysis
Process performance evaluation
Interpretation of simulation results
Future Scope

The simulation can be further developed by performing:
Temperature sensitivity analysis
Oxygen-to-methane ratio optimization
Pressure sensitivity analysis
Methane conversion analysis
Hydrogen yield optimization
Comparison with steam methane reforming
Energy and heat-duty analysis
Process economics and optimization
