Numerical Simulation of the Supercritical Piston Effect (BSc Thesis)

Overview

This repository contains the numerical simulation code and research paper for my Mechanical Engineering Bachelor's thesis. The project investigates heat transfer in supercritical fluids, specifically focusing on the "Piston Effect" (adiabatic heating) phenomena.

Repository Contents

  src/: Python implementation of the numerical solver.

  Szuperkritikus_dugattyuhatas.pdf: My TDK (Scientific Student Conference) paper.
    Language: Hungarian
    Focus: Initial condition dependence of the supercritical Piston Effect.

Methodology

The simulation is based on Boukari’s equations for thermodynamic fluid flow. The project was divided into two distinct modeling phases:

1. Linear Simulation (Constant thermophysical properties)

    Approach: Linearized the governing equations using constant thermophysical properties.

    Objective: To isolate and investigate the dependence of the Piston Effect on initial conditions.

2. Nonlinear Simulation (State-dependent thermophysical properties)

    Approach: Implemented full nonlinear equations where material properties change dynamically with state variables.

    Key Findings:

     Significant deviations from the linear model were observed at higher heat inputs.

     The nonlinear model successfully captures the thermodynamic complexity required for high-energy transient responses.
