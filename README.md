# Pedagogical-Biogem-UI-for-cGENIE-Climate-Model
The cGENIE model is an intermediate complexity Earth System Model created by Andy Ridgewell which includes atmosphere, ocean, and biogeochemistry components. To make this powerful tool more accessible to undergraduates, I am creating a self-documented pedagogical user interface for visualizing model output. The interface will include explanations of parameters, functions, and computation behind cGENIE. It is built in MATLAB from muffin-plot master by Andy Ridgwell (derpycode).

File Structure

BiogemApp.mlapp : the UI script
UI_biogem_2d.m : altered plot_fields_biogem_2d.m to be compatible with UI
UI_biogem_3d_k.m : altered plot_fields_biogem_3d_k.m to be compatible with UI
UI_biogem_3d_i.m : altered plot_fields_biogem_3d_i.m to be compatible with UI
UI_crossplotc.m : altered plot_crossplotc.m to be compatible with UI
UI_histc_2d.m : altered plot_histc_2d.m to be compatible with UI

Using the interface:
- Download the Biogem-UI folder
- Run BiogemApp.mlapp with MATLAB after adding your experiment folder (with netCDF file) into the same folder


Contribution: To contribute to this project contact Isabelle Pfander (irpfander) on Github
Credits: Andy Ridgwell (derpycode) muffinplot 
Prerequisite: MATLAB - built with R2019 (9.6.0.1174912)

