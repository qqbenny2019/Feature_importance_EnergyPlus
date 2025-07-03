# Feature_importance_EnergyPlus

It is a resository for calculating feature importance of energy-saving factors in Plant Factories with Artificial Light (PFAL) using EnergyPlus.

Reference: Energy-saving effect assessment of various factors in container plant factories: A data-driven random forest approach (https://doi.org/10.1016/j.cles.2024.100122)

Energy-saving factors: wall heat transfer coefficient, outer surface solar reflectivity, outer surface infrared emissivity, infiltration, orientation, air conditioner COP, light efficacy

Feature importance calculation method: random forest

Data source: EnergyPlus batch calculation file with Python API (https://eppy.readthedocs.io/en/latest/contributing.html)

----------------------File introduction---------------------------------
20-inch-container-modified.idf: EnergyPlus initial file (base file for Python API);
4 .epw files: weather files for four cities;
Energy of PFAL-different cases simple.ipynb: Python file for controlling batch calculation of EnergyPlus files (only for lettuce)
Energy of PFAL-different plant varities.ipynb: Python file for controlling batch calculation of EnergyPlus files (for different plant varities)
V22-1-0-Energy+.idd: initial file for EnergyPlus software
random forest.ipynb: Python file to calculate feature importance using random forest
