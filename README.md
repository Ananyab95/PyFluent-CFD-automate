# Automated Pipe Flow CFD Using PyFluent

## Overview

This project develops an automated CFD workflow using **Python, PyFluent, and Ansys Fluent** to simulate incompressible flow through a circular pipe.

### What I did

- Automated Fluent **mesh setup, case setup, solver execution, and post-processing** using PyFluent.
- Performed a **mesh-independence study** based on mass balance, pressure drop, friction factor, and flow development.
- Verified CFD results against **analytical pipe-flow solutions and engineering correlations**.
- Investigated the effect of **Reynolds number** on pressure drop and friction factor across laminar and turbulent flow regimes.
- Automated extraction of simulation results for further analysis.

### Why I did it

The goal was to reduce repetitive manual CFD setup and demonstrate that a simulation workflow can be made **reproducible, scalable, and engineering-verified**, rather than simply automating Fluent operations.

### Where it's going

The next stage is to develop a **parameter-driven CFD workflow** capable of automatically running multiple configurations and generating a structured CFD dataset.

Future extensions will include:

**Parametric CFD → DOE → CFD dataset → AI/ML surrogate modeling**


The geomtery, material properties and mesh type are as follows:-
| Parameter         |      Value |
| ----------------- | ---------: |
| Pipe diameter     |      25 mm |
| Pipe length       |        1 m |
| Inlet velocity    |    0.5 m/s |
| Pressure outlet   |      1 bar |
| Density           |  847 kg/m³ |
| Dynamic viscosity |  0.02 Pa·s |
| Mesh              | Polyhedral |
