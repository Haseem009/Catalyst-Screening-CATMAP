# Catalyst-Screening-CATMAP
Microkinetic modeling and catalyst screening for HER using CATMAP.
# Hydrogen Evolution Reaction (HER) Catalyst Screening Using CATMAP

## Project Overview

Computational study of the Hydrogen Evolution Reaction (HER) using CATMAP-based microkinetic modeling to evaluate and compare catalyst performance.

## Objectives

- Model the Volmer, Heyrovsky, and Tafel reaction pathways.
- Compare catalyst activity using hydrogen adsorption free energy (ΔG_H*).
- Analyze hydrogen production rates and surface coverage.
- Generate HER volcano plots to identify promising catalysts.
- Identify rate-determining steps for different catalyst classes.

## Catalysts Studied

Pt, Pd, Cu, Rh, Ni, Ag, Co, Ru, Au, and Re.

The study also discusses promising non-precious catalyst alternatives including MoS₂ and WC. :contentReference[oaicite:0]{index=0}

## Methodology

The project uses CATMAP, an open-source Python framework for microkinetic modeling. DFT-derived energetic parameters are used to calculate reaction rates, surface coverages, turnover frequencies (TOF), and catalyst activity. :contentReference[oaicite:1]{index=1}

### Simulation Conditions

- Electrolyte: Acidic, pH 0
- Potential: 0 V vs. RHE
- Temperature: 298 K
- Surface model: Ideal flat (111)
- Reaction pathways: Volmer–Heyrovsky–Tafel :contentReference[oaicite:2]{index=2}

## Key Results

The catalyst screening identified Pt as the highest-performing catalyst in the reported dataset, with an H₂ production rate of approximately **8.19 × 10⁻⁴ mol/s** and ΔG_H* of **−0.02 eV**. :contentReference[oaicite:3]{index=3}

The analysis demonstrates the volcano relationship between HER activity and hydrogen binding energy, with optimal activity occurring near ΔG_H* ≈ 0 eV. :contentReference[oaicite:4]{index=4}

## Tools & Skills

- CATMAP
- Python
- Microkinetic Modeling
- Computational Catalysis
- Catalyst Screening
- Reaction Kinetics
- DFT-derived Energetic Data
- Volcano Plot Analysis
- Hydrogen Production Analysis

## Project Report

The complete project report is included in this repository.
