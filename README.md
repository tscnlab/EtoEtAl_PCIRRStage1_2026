# DLE-SENSE Registered Report: Stage 1 manuscript and simulation code / outcomes
This repository contains the manuscript and simulation code / outcomes for the Stage 1.

The simulations were conducted to inform the planned sample size and to assess the analysis of the association between daytime melanopic equivalent daylight illuminance (EDI) dose and evening melatonin suppression.

# Contents
The `manuscript` folder contains manuscript files (.docx and .pdf)

The `scripts` folder contains three R Markdown Files:

1. `informed_data_simulation_DLE-SENSE.Rmd`
Generates plausible parameters values using existing data.
2. `bfda_simulations_parallelised_DLE-SENSE.Rmd`
Conducts the Bayes factor design anaysis and assesses the estimation of random slopes with three observations per participant.
3. `bfda_recuitment_missingness_sensitivity_DLE-SENSE.Rmd`
Examines the effect of missing observations and the planned recruitment procedure.

Input data and intermediate files used by the scripts are also included in the  `scripts` folder.
Simulation results are stored in `scripts/results`.
