# WR229-Waveguide-Design-CST


## Overview
This project involves the design and electromagnetic simulation of a **WR229 Rectangular Waveguide** using **CST Studio Suite**. The study covers the analysis of propagation modes, S-parameters, and the effects of dielectric loading on waveguide performance.

## Key Features
* **Full-Wave Simulation:** Modeled in CST Studio Suite using the Time Domain Solver.
* **Dielectric Loading Analysis:** Comparative study between an air-filled waveguide and a partially dielectric-filled version.
* **S-Parameter Characterization:** Analysis of Return Loss (S11) and Insertion Loss (S21).
* **Field Distribution:** Visualization of Electric (E) and Magnetic (H) field distributions for the TE10 mode.

## Technical Specifications
* **Waveguide Standard:** WR229 (Dimensions: 2.290 x 1.145 inches).
* **Frequency Range:** 3.30 GHz to 4.90 GHz (C-Band).
* **Cutoff Frequency:** Approximately 2.58 GHz for the dominant TE10 mode.
* **Material Analysis:** Comparison using FR4/Teflon or other dielectric inserts to observe phase shifts and impedance matching.

## Design Methodology
1. **Geometric Modeling:** Precise 3D modeling of the waveguide structure.
2. **Boundary Conditions:** Setting up PEC (Perfect Electric Conductor) and Waveguide Ports.
3. **Meshing:** Optimization of hexahedral mesh cells for accurate field computation.
4. **Parameter Sweeps:** Analyzing the impact of varying dielectric thickness on the shift in resonant frequency.

## Results & Visuals

WR229 Waveguide E-Field Distribution

![half_dielectric_electric_field](https://github.com/user-attachments/assets/e8200601-9b96-47c8-9342-a40c7ff486cf)

s parameters

![S-Parameters Graph](https://github.com/user-attachments/assets/7d2ef07e-6a11-4de5-9ec4-36c390c784da)



## Software Tools
* **CST Studio Suite:** EM Simulation.

