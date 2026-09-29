# Python-Based Techno-Economic Analysis (TEA) Framework

A generic, data-driven Python framework for the techno-economic assessment (TEA) of chemical process plants.

## Overview
This framework was developed as part of a Master's Project Thesis in **Hydrogen Technology** at **Technische Hochschule Rosenheim (Campus Burghausen)**. It decouples process data from calculation logic: all process flowsheet data, equipment specifications, cost factors, and financial parameters are supplied via standardized Excel workbooks without modifying the source code.

## Key Features
- **Flexible Capital Costing:** Parallel factorial estimation (Lang factor), cascading structures (NETL convention), and single indirect adders.
- **Operating Cost Engine:** Explicit item-based resolution and lumped formulation (Turton).
- **Automated Solvers:** Brent's method root-finding for Internal Rate of Return (IRR) and target-return product selling price.
- **Input Validation Stage:** Pre-execution screening to catch inconsistencies (e.g., double-counted installation factors, exchange-rate inversions).
- **Automated Sensitivity Analysis:** One-at-a-time parameter sweeps and automated Tornado chart generation.

## Benchmark Validation
The tool has been validated against three peer-reviewed published studies:
1. **Power-to-Methanol:** Integrated alkaline electrolysis & CO2 hydrogenation (Gelten et al., 2026)
2. **Chemical Looping Reforming:** Three-reactor system for H2 production (Khan & Shamim, 2016)
3. **Biomass Gasification to Ammonia:** Pressurized entrained-flow system (Andersson & Lundgren, 2014)

## Author
- **Mastaneh Behtash** (M.Sc. Hydrogen Technology, TH Rosenheim)
