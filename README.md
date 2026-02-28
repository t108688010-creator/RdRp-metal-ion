Molecular Dynamics Simulations of SARS-CoV-2 RdRp with Metal Ion Substitutions
This repository contains the input files, topology parameters, and analysis scripts for the molecular dynamics (MD) simulations of the SARS-CoV-2 RNA-dependent RNA polymerase (RdRp) complex.

📌 Project Overview
This study investigates the structural stability and binding affinity of the SARS-CoV-2 RdRp active site when the native Mg2+ ions are substituted with other divalent metal ions (Mn2+, Ca2+, Zn2+, Co2+). The aim is to understand how different metal ions influence the positioning of the Nucleoside Triphosphate (NTP) and the overall catalytic environment.

💻 Simulation DetailsSoftware: 
GROMACS 2016 
Force Field: AMBER99SB-ILDN 
Water Model: TIP3P
Ensemble: NPT (310 K, 1 bar)
Time Step: 2 fs
Total Simulation Time: 150 ns per system

.
├── parameters/             # .mdp files for EM, NVT, NPT, and Production MD
├── systems/                # Initial .gro and .top files for each metal ion system
│   ├── Mg-RdRp-NTP/
│   ├── Mn-RdRp-NTP/
│   ├── Ca-RdRp-NTP/
│   ├── Zn-RdRp-NTP/
│   └── Co-RdRp-NTP/
├── topology/               # .itp files for ligands and metal ion parameters
└── README.md