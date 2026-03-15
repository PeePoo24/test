# Parametric Study of Photovoltaic–Thermoelectric Generator with Passive Thermal Management

## Overview

This project investigates the performance of an integrated **Photovoltaic–Thermoelectric Generator (PV-TEG) system with passive thermal management using Phase Change Materials (PCMs)**.

Photovoltaic systems convert solar radiation into electrical energy, but a significant portion of the absorbed energy is converted into heat. This heat increases the operating temperature of the PV module and reduces its efficiency.

To address this limitation, this study integrates:

• **Photovoltaic module (PV)**
• **Thermoelectric generator (TEG)**
• **Phase change material (PCM)**

The thermoelectric generator converts part of the waste heat from the PV module into additional electrical energy, while the PCM stabilizes the temperature of the system through latent heat storage. This combination improves thermal stability and enhances the overall energy conversion efficiency of the hybrid system.

This work was conducted as part of a **Bachelor of Technology project at Shri Mata Vaishno Devi University**. 

---

# Hybrid PV–TEG–PCM System Concept

## Energy Balance of PV-TEG-PCM System

![Energy Balance](figures/energy_balance_system.jpg)

The PV-TEG-PCM system captures solar radiation and distributes energy into electrical output and thermal energy flows. The PV module converts solar radiation into electricity, while the remaining heat flows to the thermoelectric generator and PCM layer for energy recovery and thermal regulation.

---

# Classification of Phase Change Materials

![PCM Classification](figures/pcm_classification.png)

Phase Change Materials (PCMs) absorb thermal energy during phase transition and release it during solidification. PCMs are generally classified into:

• Organic PCMs (paraffins, fatty acids)
• Inorganic PCMs (salt hydrates, metallic materials)
• Eutectic PCMs (mixtures with controlled melting temperatures)

These materials are used for passive thermal management of photovoltaic modules.

---

# PV-PCM System Configuration

![PV PCM System](figures/pv_pcm_schematic.png)

This schematic shows the arrangement of the photovoltaic module with a PCM layer. The PCM absorbs excess heat from the PV module and stabilizes its temperature during peak solar irradiation.

---

# PV-TE Hybrid System Configuration

![PV TE Hybrid System](figures/pv_te_system.png)

The PV-TE hybrid system integrates a thermoelectric generator at the rear surface of the photovoltaic module. The temperature difference between the hot side (PV surface) and cold side generates electrical power through the Seebeck effect.

---

# Energy Balance of PV-TE Hybrid System

![Energy Balance Hybrid](figures/pv_te_energy_balance.png)

The hybrid system distributes energy into:

• PV electrical power output
• Thermoelectric generator power output
• Thermal losses (convection and radiation)

The TEG recovers part of the conductive heat losses from the PV module.

---

# Efficiency Variation with Temperature Difference

![Efficiency Graph](figures/pv_te_efficiency_graph.png)

This figure shows the variation of:

• PV efficiency
• Thermoelectric generator efficiency
• Hybrid PV-TE efficiency

as a function of **temperature difference across the thermoelectric generator (ΔT)**.

Key observations:

• PV efficiency decreases as temperature increases
• TEG efficiency increases with higher temperature difference
• Hybrid system efficiency improves due to combined energy conversion

---

# Material Comparison Study

The performance of the hybrid system was analyzed for different photovoltaic materials:

• **Amorphous Silicon (a-Si)**
• **Monocrystalline Silicon (Mono-Si)**
• **Cadmium Telluride (CdTe)**

These materials exhibit different temperature coefficients and efficiency characteristics.

---

## a-Si PV-TE Hybrid System

![a-Si Graph](figures/a_si_results.png)

Amorphous silicon cells show lower efficiency but better temperature stability compared to crystalline silicon.

---

## Mono-Si PV-TE Hybrid System

![Mono Si Graph](figures/mono_si_results.png)

Monocrystalline silicon cells provide higher baseline efficiency but experience greater efficiency degradation with increasing temperature.

---

## CdTe PV-TE Hybrid System

![CdTe Graph](figures/cdte_results.png)

Cadmium telluride cells demonstrate moderate efficiency with good thermal stability.

---

# MATLAB Simulation

The hybrid system was simulated using MATLAB to evaluate:

• PV efficiency degradation with temperature
• Thermoelectric generator efficiency
• Hybrid system efficiency
• Hybrid power output

The model uses temperature-dependent efficiency equations and thermoelectric material properties such as Seebeck coefficient, electrical resistivity, and thermal conductivity.

---

# Key Findings

• Photovoltaic efficiency decreases with increasing temperature.
• Thermoelectric generators can recover part of the waste heat from PV modules.
• Phase Change Materials improve thermal stability of the system.
• Hybrid PV-TE-PCM systems can enhance overall solar energy utilization.
• Material selection significantly influences hybrid system performance.

---

# Project Structure

```
pv-teg-pcm-hybrid-system
│
├── matlab
│   ├── pv_te_simulation.m
│
├── figures
│   ├── energy_balance_system.png
│   ├── pcm_classification.png
│   ├── pv_pcm_schematic.png
│   ├── pv_te_system.png
│   ├── pv_te_energy_balance.png
│   ├── pv_te_efficiency_graph.png
│   ├── a_si_results.png
│   ├── mono_si_results.png
│   └── cdte_results.png
│
├── report
│   └── project_report.pdf
│
└── README.md
```

---

# Author

**Zafir Ashraf Beigh**
B.Tech Mechanical Engineering
Shri Mata Vaishno Devi University

Research interests:

• Renewable Energy Systems
• Hybrid Energy Systems
• Solar Energy Modeling
• Thermal Energy Management
