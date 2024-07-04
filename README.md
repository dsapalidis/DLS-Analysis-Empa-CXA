# DLS-Data-Modeling-Empa-CXA
Software and useful python tools for data processing and analysis of Multi-angle Dynamic Light Scattering data (from ZetaSizer or other instruments)

<h1 align="center">
<img src="https://github.com/dsapalidis/mypackage/blob/Sapd-Tutorial/Sapaempa.svg" width="400">
</h1><br>

   
Multi-angle Dynamic Light Scattering (MA-DLS) software and tools is a Python package containing mostly jupyter notebooks that enables:
1. Reading of the exported data from a ZetaSizer (Malvern Panalytical) DLS instrument (or other DLS instruments) and create seperate .txt files for each angle and sample
2. Nornalization and fitting of the experimental correlation function via two possible models: i. non-linear iteration model (cumulants) and ii. bi-exponential
3. Calculation of diffusion coefficient, hydrodynamic radius and storage of all the fitting results for each sample and angle into a single table
4. User selection of the number of the angles that will be used for averaging. Evaluation of the robustness of the fitting using the linear curve of Γ-q^2 for each angle.
   

- **Website:** https://www.empa.ch/web/s499
- **Bugs** dsapalidis@gmail.com
