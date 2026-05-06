# pySFE
Prediction of Stacking Fault Energies using thermodynamic approach

# Stacking Fault Energy Predictor

A Python based GUI application for predicting stacking fault energy (SFE) in High manganese steels including TWIP, Hadfield, Alloy steels, TRIP, etc.., using thermodynamic approaches.

# Features

- Input fields for alloy composition: Fe, Mn, Cu, Si, C, N, Cr, etc. (wt%)
- Optional temperature input (default set to 293 K)
- Calculate SFE using chemical and magnetic contributions based on thermodynamic models such as Olson and Cohen, Ferr (refer references)  
- Visualize SFE and its components vs temperature with plots

# Usage

Running the application:

# Method 1:

Double click or open it as administrator 'pySFE.exe' file and provide the necessary inputs in the main window and click calculate SFE to see the results and the predicted deformation mechanisms. Blanked values (unspecified values) are assigned with zeroes. Compositions are in wt%, and SFE in mJ/m².
(i) Click "Calculate SFE" to compute SFE. You can play with the temperature as well.
(ii) Click show plots for different contributions and SFE values as a function of temperature. 
(iii) Click save plots to save the figure as PNG plots.

# Method 2:
Locate the .exe folder and run

```bash
pySFE.exe

```
and follow the method 1 steps (i, ii, iii)

# Model details

The prediction uses thermodynamic formulas including:
- Gibbs energy changes for phase transformation
- Excess terms and magnetic contributions
- Temperature-dependent calculations

Click "Show Plots" to display four plots:
1. Chemical SFE contribution vs temperature
2. Magnetic SFE contribution vs temperature
3. SFE and its components (chemical, magnetic, interfacial, total)
4. Total SFE vs temperature with room temperature annotation

Note: For accurate predictions, TEM or other characterization methods described in the literature may be employed.

# Coupling Thermo-Calc:

A valid TC license can be coupled with pySFE to compute SFE of other systems as well.

# References:
- S. Curtze and V. T. Kuokkala, “Dependence of tensile deformation behavior of TWIP steels on stacking 
fault energy, temperature and strain rate,” Acta Mater., vol. 58, no. 15, pp. 5129–5141, 2010.
- S. Curtze, V. T. Kuokkala, A. Oikari, J. Talonen, and H. Hänninen, “Thermodynamic modeling of the 
stacking fault energy of austenitic steels,” Acta Mater., vol. 59, no. 3, pp. 1068–1076, 2011.
- M. Ghasri-Khouzani and J. R. McDermid, “Effect of carbon content on the mechanical properties and 
microstructural evolution of Fe-22Mn-C steels,” Mater. Sci. Eng. A, vol. 621, pp. 118–127, 2015.
- R. Xiong, H. Peng, S. Wang, H. Si, and Y. Wen, “Effect of stacking fault energy on work hardening 
behaviors in Fe-Mn-Si-C high manganese steels by varying silicon and carbon contents,” Mater. Des., 
2015
- A. Dumay, J. P. Chateau, S. Allain, S. Migot, and O. Bouaziz, “Influence of addition elements on the 
stacking-fault energy and mechanical properties of an austenitic Fe-Mn-C steel,” Mater. Sci. Eng. A, vol. 
483–484, no. 1-2 C, pp. 184–187, 2008.
- Y. N. Dastur and W. C. Leslie, “Mechanism of Work Hardening in Hadfield Manganese Steel.,” Metall. 
Trans. A, Phys. Metall. Mater. Sci., vol. 12 A, no. 5, pp. 749–759, 1981. 
- R. Xiong et al., “Effects of Si on the Microstructure and Work Hardening Behavior of Fe‒17Mn‒1.1C
xSi High Manganese Steels,” Met. Mater. Int., no. 0123456789, 2020.
- J. K. Hwang, “Deformation behaviors of various Fe–Mn–C twinning-induced plasticity steels: effect of 
stacking fault energy and chemical composition,” J. Mater. Sci., vol. 55, no. 4, pp. 1779–1795, 2020. 
- Raami, L., et al. "Stacking fault energy and deformation mechanism of high-Mn steels"
  Materials Science and Engineering A 528.13-14 (2011): 4136-4142.
- Allain, S., "TMultiscale characterization and modeling of the thermomechanical deformation and hardening mechanisms of high manganese austenitic steels : focus on the TWIP effect", PhD thesis, LPM - Laboratoire de physique des matériauxm, Ecole des Mines de Nancy, 2004.


# Developed by
Dr. J P Arul Mozhi Varman

Should you require your own database or develop materials with tailored deformation mechanisms, please reach out; 
jp.arulmozhivarman@uq.net.au
materialtechnologists@gmail.com
