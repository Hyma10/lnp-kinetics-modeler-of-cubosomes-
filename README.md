# lnp-kinetics-modeler-of-cubosomes-
Python-based mathematical simulation modeling lipid nanoparticle (cubosome) structural phase transitions and membrane interaction kinetics. DOI: 10.1021/acs.jpcb.4c06060
# LNP-Kinetics-Modeler 🧪📊

A computational simulation script designed to model the structural phase transition kinetics of lipid nanoparticles (cubosomes) when interacting with model cell membranes. 

## Background & Rationale
Based on biophysical insights from literature (**DOI: 10.1021/acs.jpcb.4c06060**), liquid-crystalline lipid nanocarriers like cubosomes undergo structural degradation and phase transitions into lamellar vesicles upon contact with fluid membranes. This open-source tool uses systems of ordinary differential equations (ODEs) to simulate these time-dependent degradation and lipid exchange rates under varying membrane fluidity states.

## Simulation Outputs

### 1. Baseline Phase Transition Kinetics
![LNP Phase Transition Kinetics](LNP%20phase%20transition%20kinetics.png)

### 2. Comparative Dynamics Across Membrane Types
The simulation models three distinct physiological conditions:
* **Baseline ($k_1=0.15, k_2=0.08$):** Standard rate of structural breakdown and membrane fusion.
* **Fluid Membrane ($k_1=0.30, k_2=0.12$):** Simulates high-fluidity bilayers that drastically accelerate the loss of the internal cubic architecture and speed up conversion into lamellar vesicles.
* **Rigid / Cholesterol-Rich Membrane ($k_1=0.05, k_2=0.03$):** Simulates rigid lipid packing (e.g., high cholesterol content) that protects the carrier and prolongs cubosome stability.

![Comparative LNP Phase Transition Dynamics](Comparitive%20LNP%20phase%20Transition%20Dynamics%20across%20membrane%20types.png) 

## Tech Stack
* **Language:** Python
* **Libraries:** SciPy (ODE solver), NumPy, Matplotlib

## How to Run
1. Open [Google Colab](https://colab.research.google.com/).
2. Copy the code from `LNP - kinetics -modeler.py`, paste it into a code cell, and run it to generate the phase portraits.
