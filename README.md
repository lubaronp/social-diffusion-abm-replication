# Social diffusion and commercial concentration: an agent-based model of customer choice

This repository contains the replication package, frozen implementation code, simulation datasets, and analysis packages for the research manuscript titled "Social diffusion and commercial concentration: an agent-based model of customer choice".

## Authors
* Luisa María Barón Porto
* Ana Cecilia Chumaceiro Hernández
* Pablo Felipe Marín Cardona

## Repository structure and file description

The repository is organized into the following frozen packages:

1. **Article_2_Codigo_v0.1.0.zip**
   Contains the complete Python 3.12.14 source code implementation of the agent-based model (ABM). Includes model initialization scripts, Watts-Strogatz network generation routines, customer choice decision rules, and simulation execution loops.

2. **Article_2_Datos_principal_T120_v0.1.0.zip**
   Primary simulation results and raw data logs across 100 paired replications up to the finite horizon T = 120. Contains system time series, vendor customer totals, and network configuration states.

3. **Article_2_Analisis_principal_T120_v0.1.0.zip**
   Analysis scripts, summary tables, and statistical evaluation code for the main experiment.

4. **Article_2_Datos_sensibilidad_parametros_v0.1.0.zip**
   Parameter sweep and sensitivity analysis dataset across the ten alternative structural and behavioral configurations.

5. **Article_2_Analisis_sensibilidad_parametros_v0.1.0.zip**
   Machine-readable analysis scripts and summary tables corresponding to the sensitivity campaign.

## Technical specifications and replication guidelines

* **Independent seed blocks:** The completed pilot experimental block uses the seed block initiated at 100000, while the main experiment uses the seed block initiated at 200000. Bootstrap confidence intervals use seed 260926 for the main experiment and 260927 for the sensitivity analysis.
* **Seed index pairing:** The sensitivity campaign deliberately reuses main seed indices 1 through 30. Replicators must preserve this pairing structure when analyzing secondary paired contrasts.
* **Software environment:** The core agent-based model simulator (v0.1.0) was developed and executed in Python 3.12.14 using exclusively modules from the Python standard library. Data post-processing, statistical analysis, and network visualization were performed using standard scientific libraries (NumPy, NetworkX, Pandas, and Matplotlib).

## License and usage

This material is provided for academic inspection, replication, and scientific review.
