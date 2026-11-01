# Low-Cost Multispectral Pipeline for Distinguishing Between PLA and PET in Resource-Constrained Recycling

An empirical machine learning pipeline and hardware simulation framework developed for a final year Bachelor of Science in Computer Science thesis at Uganda Christian University (UCU).

## Project Overview
This project addresses the technical challenge of distinguishing Polylactic Acid (PLA) bioplastics from Polyethylene Terephthalate (PET) using low-cost multispectral sensors in resource-constrained environments. By leveraging algorithmic operational filtering and mathematical feature engineering, this pipeline rescues low-cost hardware configurations to a highly actionable classification accuracy.

## Simulation Pipeline Performance Progress
1. **Phase 1: Raw Unfiltered Baseline (AS7421 Window)**: 56.52% (Fails due to environmental noise)
2. **Phase 2: Operational Waste Filter ($\geq$ 15% Conc.)**: 75.00% (Isolates macroscopic flakes)
3. **Phase 4: Advanced Pipeline Optimization (First Derivative)**: 87.50% (Rescues low-cost hardware)

## Engineering Design Choice
Empirical simulation results show that the AS7421 (850-1050 nm) and the cheaper AS7265x Triad (850-940 nm) reach identical performance ceilings (87.50%). To satisfy the resource-constrained criteria of the thesis title, the pipeline utilizes the AS7265x Triad sensor array to minimize assembly costs without compromising sorting accuracy.
