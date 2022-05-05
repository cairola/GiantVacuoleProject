# Simulations of giant vacuoles
Repository with all Wolfram Mathematica notebooks developed for simulations of giant vacuoles  


## Usage 

Follow inline comments. 
For the biological meaning of the model parameters, refer to manuscript.  


## Description 

### equilibria.nb

This notebook generates steady-state configurations of giant vacuoles according to our proposed biophysical model (Eq.3 of the manuscript).
It then analyses the dependence of various physical parameters on the perfusion pressure drop. 
Parameters analysed are: 
- vacuole area, cross-section, volume, opening angle, surface tension; 
- intracellular pressure;
- outer cell area and surface tension;
- total area strain. 
It also generates a plot of vacuole tension vs. surface area. 

### variability.nb

This notebook investigates how robust are the characteristic feratures of steady-state configurations of giant vacuoles against physiological variability. 
It generates N configurations for sets of parameters chosen randomly from a reference set while including 20% variability in the parameters values.  

### stability.nb

This notebook studies the linear stability of the configurations of giant vacuoles. 
It calculates numerically the force exerted on the vacuoles upon perturbation of the vacuole radius. 

### dynamics.nb

This notebook generates temporal trajectories of the configurations of giant vacuoles according to our proposed biophysical model (Eqs. 1 and 2 of the manuscript). It then analyses the dependence of various physical parameters on time for fixed perfusion pressure drop (three cases studied). 
Parameters analysed are: 
- vacuole area, cross-section, volume, opening angle, surface tension; 
- intracellular pressure;
- outer cell area and surface tension;
- total area strain. 

### dynamics_ensemble.nb

This notebook investigates how robust are the characteristic feratures of temporal trajectories of the configurations of giant vacuoles against physiological variability. 
It generates N configurations for sets of parameters chosen randomly from a reference set while including 20% variability in the values of dynamical parameters: viscosity; timescale for actin polymerization and myosin recruitment.  

### kinetic.nb

This notebook investigates how robust are the characteristic feratures of temporal trajectories of the configurations of giant vacuoles against physiological variability. 

### thickness.nb
