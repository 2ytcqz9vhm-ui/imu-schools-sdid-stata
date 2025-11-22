# imu-schools-sdid-stata
STATA code for my dissertation evaluating the impact of the Independent Monitoring Unit (IMU) reform in Khyber Pakhtunkhwa, Pakistan, on teacher attendance and child learning outcomes.
# Impact of the Independent Monitoring Unit (IMU) Reform – STATA Code

This repository contains the STATA code used for my dissertation evaluating the impact of the Independent Monitoring Unit (IMU) reform in Khyber Pakhtunkhwa, Pakistan, on teacher attendance and child learning outcomes. The analysis uses district-level ASER panel data (2012–2018) and applies the Synthetic Difference-in-Differences (SDID) method.

## Overview
The code in this repository cleans the ASER dataset, prepares treatment and control groups, implements SDID, and generates all tables and figures included in the dissertation. Everything is contained in this single do-file.

## Data
- **ASER Pakistan** district-level panel data (2012–2018)  
- **IMU reform rollout** timeline for treated districts  
- Data files are **not included** in this repository due to access restrictions.  
- Update the file paths inside the `.do` files to point to your local data directory.

## Methodology
- Synthetic Difference-in-Differences (SDID)
- Robustness checks: placebo tests, sensitivity checks, and alternative specifications
- Outcome variables:
  - Teacher attendance
  - Student learning outcomes (literacy and numeracy measures)
