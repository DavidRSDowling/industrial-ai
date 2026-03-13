# Industrial AI & Machine Learning Project

Personal learning project building industrial AI skills, combining a 15+ year 
background in electrical & instrumentation engineering with Python, machine learning, 
and agentic AI.

## About
E&I Engineer and Data & Connectivity Manager at TotalEnergies transitioning into 
Industrial AI/ML Engineering. This repository documents the learning journey — 
from Python foundations to machine learning models to agentic AI systems — 
applied to real industrial and energy datasets.

## Projects

### 🏠 Home Energy Analysis (Sprint 1)
**File:** `home_energy_analysis.ipynb`

Analysis of 33 months of real home energy data (May 2023 – Jan 2026) covering:
- Monthly energy flows: solar production, grid import/export, EV charging
- Heat pump vs gas boiler comparison with COP estimation (~5.86)
- Monthly cost and income breakdown
- EV charger profitability analysis

**Key finding:** Heat pump installation (Aug 2025) reduced heating season energy 
costs from ~€700/month to ~€200/month while achieving a real-world COP of 5.86 — 
consistent with expected performance given brine temperatures and 33°C underfloor 
heating flow temps.

**Tools:** Python, pandas, matplotlib, seaborn

### 🏭 Industrial Data Cleaning (Sprint 1)
**File:** `sprint1_data_cleaning_v2.ipynb`

Simulated CNG/H2 refuelling station pressure data with injected fault signatures:
- Clipping detection (PLC range errors)
- Spike detection using Median Absolute Deviation (MAD)
- Slow drift detection using hourly resampling and rate-of-change analysis
- Sequential cleaning pipeline — order matters

**Tools:** Python, pandas, numpy, matplotlib

## Tech Stack
Python 3.13 | pandas | numpy | matplotlib | seaborn | VS Code | conda | Git

## Roadmap
- **Phase 1 (Current):** Python & Data Foundations
- **Phase 2:** Machine Learning & Predictive Maintenance
- **Phase 3:** Agentic AI & LLMs
- **Phase 4:** Deployment & Portfolio

## Background
15+ years E&I engineering across mining, water treatment, and hydrogen/CNG mobility.
Functional Safety Expert (IEC 61511/62061) | ATEX Expert | PLC/SCADA experience.
Currently managing data and connectivity for 120+ CNG stations and 8 H2 refuelling 
stations across France, Belgium and The Netherlands at TotalEnergies.
```