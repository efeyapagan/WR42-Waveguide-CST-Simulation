# WR-42 Rectangular Waveguide Design and CST Simulation

This project investigates the electromagnetic propagation characteristics of a WR-42 rectangular waveguide using CST Studio Suite.

## Project Overview

The dominant TE10 mode cutoff frequency was analytically calculated and verified via full-wave simulation.

- Waveguide Type: WR-42
- Dimensions: a = 10.668 mm, b = 4.318 mm
- Calculated cutoff frequency (TE10): ≈ 14.05 GHz
- Simulation Tool: CST Studio Suite (Time Domain Solver)

## Key Analyses

### 1. Empty Waveguide Analysis
- S21 transmission analysis
- Verification of cutoff frequency
- Electric field distribution above and below cutoff

### 2. Partial Dielectric Loading
- Half-filled waveguide (εr = 5)
- Impedance mismatch observation
- Cutoff shift analysis
- Field confinement comparison

## Results

- The simulated -3 dB transition point closely matches theoretical cutoff.
- Dielectric loading introduces impedance mismatch and shifts efficient propagation frequency.
- E-field analysis confirms propagation vs evanescent behavior.

## Skills Demonstrated

- Electromagnetic Theory
- Waveguide Modal Analysis
- S-Parameter Interpretation
- RF Simulation (CST)
- Dielectric Loading Effects

---

## Reproduce This Project

You can replicate the same CST setup by following the step-by-step guide in the included report:

- `Wave_Guide_CST_MANUAL_EfeYapagan_EgemenDiler.pdf` → complete instructions (CST template selection, geometry creation, ports, frequency range, S21 and E-field analysis)

Just follow the report sequentially and you will obtain the same results.

> Note: CST Studio Suite is required to run the simulation files.
