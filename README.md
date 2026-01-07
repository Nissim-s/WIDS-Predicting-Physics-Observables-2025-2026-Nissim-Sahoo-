# Predicting Physics Observables from LHC Data

This repository contains a structured report and preliminary analysis of high-energy physics data from the Large Hadron Collider (LHC). The project focuses on exploring ROOT files, understanding the internal structure of the data, and analyzing reconstructed heavy-flavor mesons ($D^*$) using Python-based tools.

---

## Project Overview

High-energy physics experiments like those at the LHC generate massive datasets that are typically stored in ROOT files. This project aims to:

- Understand the internal structure of ROOT files.
- Inspect and process event-wise and aggregated analysis data.
- Analyze $D^*$ meson candidates using topological, kinematic, and PID variables.
- Prepare a self-contained LaTeX report documenting all steps.

The analysis workflow includes:

1. Opening and exploring ROOT files using `uproot`.
2. Extracting TTree and histogram data.
3. Converting ROOT trees to pandas DataFrames for inspection.
4. Analyzing decay topologies and transverse momentum distributions.
5. Preparing a LaTeX report documenting methods, equations, and results.

---

## Repository Structure

