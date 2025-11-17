# Conditional_Monitoring_Wind_Turbine_Blades
This repository contains a full workflow for analysing the structural health of wind turbine blades using operational vibration measurements. The project applies Frequency Domain Decomposition (FDD), Stochastic Subspace Identification (SSI), MAC analysis, and time- and frequency-domain techniques to detect stiffness loss, mass changes, abnormal damping, and blade-specific anomalies.

The analysis covers all three blades (B1, B2, B3) across two turbines, using both broadband vibration data and derived mode shapes.

'''text
📦 WindTurbine-Blade-Condition-Monitoring
│
├── Data_Cleaning_Visualistion.ipynb      → Preprocessing & initial inspection  
├── Time_Domain_Analysis.ipynb            → RMS, peaks, kurtosis, trending  
├── Spectral_Analysis.ipynb               → FFT, PSD, coherence, FDD  
│
├── Modal_Analysis-Blade_1.ipynb          → SSI & mode shapes for Blade 1
├── Modal_Analysis-Blade_2.ipynb          → SSI & mode shapes for Blade 2
├── Modal_Analysis-Blade_3.ipynb          → SSI & mode shapes for Blade 3
│
├── Turbine_1.csv                          → Cleaned vibration dataset (Turbine 1)
├── Turbine_2.csv                          → Cleaned vibration dataset (Turbine 2)
│
├── batch_121219_combined.csv              → Original raw dataset batch 1 (Turbine 1)
├── batch_199672_combined.csv              → Original raw dataset batch 2 (Turbine 2)
│
├── mode_shapes.xlsx                       → Extracted mode shapes & damping
│
└── README.md                              → Project documentation
'''
