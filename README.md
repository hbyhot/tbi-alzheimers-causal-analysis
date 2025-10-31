# Causal Inference Analysis of Traumatic Brain Injury and Alzheimer's Disease Progression

This repository contains code and analysis from a collaborative research project 
with Prisma Health (2020–2021), examining the causal effect of traumatic brain injury (TBI) 
on Alzheimer's disease progression using longitudinal diffusion tensor imaging (DTI) data.

## Dataset
- 961 subjects (TBI vs non-TBI)
- Longitudinal DTI scans
- 249 imaging-derived biomarkers
- Cohort matching and clinical variable harmonization performed prior to analysis

**Note:** Raw DTI data cannot be shared here due to data use agreements. 
Code and synthetic example data will be provided for reproducibility.

## Methods
- Propensity score and cohort matching (SAS / SQL)
- Longitudinal mixed-effects modeling (R)
- Quantile regression for biomarker distributional shifts
- Visualization and interpretation of neurodegeneration patterns

## Key Findings
- TBI history is associated with accelerated microstructural degeneration
  in white matter regions implicated in memory and cognitive function.
- Results support biomarker-driven risk stratification for cognitive decline.

## Tools
- SAS, SQL (data processing & cohort matching)
- R (lme4, nlme, quantreg)
- Python (data visualization and figure generation)

## Status
Code organization and documentation are in progress.
