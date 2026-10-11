# Social Diffusion and Commercial Concentration: An Agent-Based Model of Customer Choice
This repository contains the replication package, frozen implementation code, simulation datasets, and analysis packages for the research manuscript titled **"Social Diffusion and Commercial Concentration: An Agent-Based Model of Customer Choice"**.
## Authors
* **Luisa María Barón Porto**
* **Ana Cecilia Chumaceiro Hernandez** 
* **Pablo Felipe Marín Cardona** 


## Repository Structure & File Description
The repository is organized into the following frozen packages:

1. **`Article_2_Codigo_v0.1.0.zip`**
   * Contains the complete Python source code implementation of the agent-based model (ABM).
   * Includes model initialization scripts, network generation routines (Watts–Strogatz), decision rules, and simulation execution loops.

2. **`Article_2_Datos_principal_T120_v0.1.0.zip`**
   * Primary simulation outputs and raw data records across the 100 paired replications up to the finite horizon $T = 120$.
   * Contains system time series, seller customer totals, and network configuration states.

3. **`Article_2_Analisis_principal_T120_v0.1.0.zip`**
   * Analysis scripts, summary tables, and statistical evaluation code for the primary experiment.

4. **`Article_2_Datos_sensibilidad_parametros_v0.1.0.zip`**
   * Parameter sweep and sensitivity analysis dataset across the ten alternative structural and behavioral configurations.

5. **`Article_2_Analisis_sensibilidad_parametros_v0.1.0.zip`**
   * Analysis scripts and machine-readable summary tables corresponding to the sensitivity campaign.


## Technical Specifications & Replication Guidelines
* **Independent Seeds:** The pilot experimental block uses seed `10000`, while the main experimental block uses seed `20000`. Bootstrap confidence intervals utilize seeds `260926` (main) and `260927` (sensitivity).
* **Seed-Index Pairing:** The sensitivity campaign deliberately reuses main seed indices `1–30`. Replicators must preserve this pairing structure when analyzing secondary paired contrasts.
* **Software Environment:** Developed and tested in Python 3.x using standard scientific computing libraries (NumPy, NetworkX, Pandas).

## License & Usage
This material is provided for academic inspection, replication, and scientific review.
