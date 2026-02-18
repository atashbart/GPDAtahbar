# GPDAtahbar
GPD-Atashbar
Numerical Modeling and Analysis of Generalized Parton Distributions
==================================================================

ABSTRACT
--------
This repository provides a numerical framework for modeling and analyzing Generalized Parton Distributions (GPDs), which encode essential information about the internal structure of hadrons in Quantum Chromodynamics (QCD).
The project is implemented as a comprehensive Jupyter Notebook and is intended for theoretical and computational studies of hadron structure, focusing on numerical evaluation, parameter dependence, and visualization of GPDs.


SCIENTIFIC BACKGROUND
---------------------
Generalized Parton Distributions unify and extend the concepts of parton distribution functions (PDFs) and hadronic form factors. They depend on three kinematic variables:

  x   : longitudinal momentum fraction of the parton
  ξ   : skewness parameter related to longitudinal momentum transfer
  t   : invariant momentum transfer squared

GPDs play a central role in the description of hard exclusive processes such as deeply virtual Compton scattering (DVCS) and deeply virtual meson production (DVMP), and provide access to spatial and spin-dependent information of hadrons.


OBJECTIVES
----------
The main objectives of this project are:

- Numerical implementation of GPD models
- Systematic exploration of parameter dependence
- Visualization and qualitative analysis of GPD behavior
- Providing a flexible computational framework for further theoretical studies


REPOSITORY STRUCTURE
-------------------
GPD-Atashbar/
│
├── GPD-Atashbar.ipynb   Main Jupyter Notebook containing models, computations,
│                       and plots
├── README.txt          Project documentation


METHODOLOGY
-----------
The project employs:

- Analytical expressions for model GPDs
- Numerical evaluation using standard scientific Python libraries
- Parametric scans over relevant kinematic variables
- Visualization via two-dimensional and three-dimensional plots

All approximations and assumptions are explicitly implemented at the model level and can be easily modified.


FEATURES
--------
- Modular definition of GPD-related functions
- Flexible control over physical parameters
- High-quality numerical visualizations
- Reproducible computational workflow
- Easy extensibility to alternative GPD models


REQUIREMENTS
------------
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Required Python libraries:
    * numpy
    * scipy
    * matplotlib


INSTALLATION
------------
Using pip:
  pip install numpy scipy matplotlib jupyter

Using conda:
  conda install numpy scipy matplotlib jupyter


USAGE
-----
1. Clone the repository:
   git clone https://github.com/atashbart/GPDAtahbar.git

2. Navigate to the project directory:
   cd GPDAtahbar

3. Launch the notebook:
   jupyter notebook GPD-Atashbar.ipynb

Run the notebook cells sequentially to reproduce all calculations and figures.


OUTPUT AND RESULTS
------------------
The notebook produces:

- Numerical evaluations of Generalized Parton Distributions
- Parametric plots showing dependence on x, ξ, and t
- Qualitative insights into the behavior of GPD models

The results are primarily intended for theoretical analysis, though the framework can be adapted for phenomenological applications.


VALIDATION AND CONSISTENCY CHECKS
--------------------------------
Where applicable, the implementation allows for:

- Forward-limit consistency checks
- Numerical stability and smoothness tests
- Qualitative comparison with known limiting behaviors


FUTURE WORK
-----------
Possible extensions of this project include:

- Implementation of more advanced GPD models
- Comparison with experimental data (e.g., JLab, HERA)
- Inclusion of QCD evolution effects
- Machine-learning-based approximation of GPDs

LICENSE
-------
This project is released under the MIT License.
You are free to use, modify, and distribute the code with proper attribution.


AUTHOR
------
Atashbar
GitHub: https://github.com/atashbart
E-MAIL: atashbart2@gmail.com

ACKNOWLEDGEMENTS
----------------
This project was developed for academic and research purposes in theoretical and computational hadron physics.
