# Echelon-utilization-of-retired-EB-batteries
Code and partial datasets for the study on echelon utilization of retired electric bus (EB) batteries: includes battery degradation modeling, economic/environmental assessment scripts, and key preprocessed  data for visualization.
# Echelon-utilization-of-retired-EB-batteries
This repository contains code for the study on **echelon utilization of retired electric bus (EB) batteries**, including modeling, assessment, and visualization modules.

This study uses GPS trajectory data of **260 electric buses in Wenzhou**.  
Due to **data privacy and security requirements**, the raw trajectory data is not publicly available in this repository.  
If you need the data for research purposes, please contact the author (22360198@zju.edu.cn).


## Project Overview
This project focuses on the lifecycle management of retired EB batteries, covering:
1. EB operational behavior characteristics analysis
2. Battery degradation modeling
3. Retired battery flow calculation
4. Economic benefit assessment
5. Parameter sensitivity analysis
6. Data visualization of key indicators


## Code Structure & File Functions
| File                          | Core Function                                                                 |
|-------------------------------|------------------------------------------------------------------------------|
| `battery degradation`         | Implements battery degradation models (calendar & cycle aging) to calculate capacity loss over time. |
| `economic benefits`           | Evaluates economic benefits of echelon utilization (peak shaving revenue, grid upgrade deferral, etc.). |
| `kmeans`                      | Uses K-means clustering to classify retired batteries based on mileage/speed features. |
| `retired battery flow`        | Calculates the quantity and capacity flow of retired batteries across years. |
| `Sensitivity analysis`        | Conducts sensitivity analysis on key parameters (e.g., battery reuse rate, peak-valley price difference). |
| `SOC sequence`                | Simulates the SOC (State of Charge) change sequence of batteries during operation. |
| `visualization-FEC_DOC_Crate` | Generates visualizations for battery performance parameters (FEC/DoC/C-rate). |
| `visualization-retired battery flow` | Visualizes the dynamic flow of retired battery quantity/capacity. |
