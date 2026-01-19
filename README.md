# Monte Carlo based simplified Calorimeter.

## Overview

This repository contains a Monte Carlo–based simulation framework for studying
**energy–time correlations in a segmented calorimeter**, motivated by trigger-level
challenges at high-luminosity hadron colliders such as the HL-LHC.

The project focuses on understanding how deposited energy, electronic noise,
pile-up, and detector timing resolution jointly determine the statistical
properties of calorimeter signals, and how this information can be exploited
for **trigger-level signal discrimination**.

---

## Physics Motivation

At the HL-LHC, hundreds of proton–proton interactions occur within a single
bunch crossing, severely degrading traditional energy-based triggers.
Precision timing provides an additional observable that enables suppression
of out-of-time pile-up and improved signal identification.

This project aims to:
- Model energy and timing measurements at the calorimeter cell level
- Quantify when timing information is statistically meaningful
- Validate energy–time correlations from first principles
- Provide a foundation for realistic trigger algorithm development

---

## Features

- Segmented calorimeter grid simulation
- Electromagnetic and hadronic shower modeling
- Gaussian electronic noise with statistical validation
- Energy-dependent timing resolution σₜ(E)
- Energy–time correlation analysis
- Trigger-motivated performance studies
- Modular design for FPGA and ML extensions

---


