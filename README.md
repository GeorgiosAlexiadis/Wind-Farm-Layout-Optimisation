# Wind Farm Layout Optimisation

## Overview

This repository contains materials related to the second stage of my bachelor's thesis, which focuses on the ***micro-scale layout optimisation*** of offshore wind farms. The study is based on a previously identified site within the ***Exclusive Economic Zone (EEZ) of the Kaliningrad region***, selected through a macro-scale multi-objective optimisation using NSGA-III.

The main file of this project is `Wind Farm Layout Optimisation.ipynb`. To explore the methods and reproduce the analysis, please download and open the notebook locally.

## Objective

The main goals of this part of the research are to:

- Optimise the spatial configuration of turbines within a defined 3×3 km² area;
- Maximise total energy production;
- Minimise wake losses due to turbine interaction.

## Methodology

The study implements the following techniques and tools:

- Analytical ***wake deficit model*** (NOJDeficit (top-hat profile)),
- Use of the ***PyWake*** library for simulating wake effects and calculating energy yield;
- ***Variable Neighborhood Search (VNS)*** metaheuristic for spatial optimisation;
- Integration of wind characteristics sourced from the ***Global Wind Atlas***.

## Results

The optimisation process resulted in turbine layouts with improved performance metrics depending on the selected wake model.

## Author

- **Georgios Alexiadis**  
- georgealeksanov90@gmail.com


Feel free to reach out for questions, collaboration, or further discussion regarding this project.
