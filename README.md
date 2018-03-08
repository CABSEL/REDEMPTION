# REDEMPTION
Reduced Dimension Ensemble Modeling and Parameter Estimation
<img style = "float: right;" src = "https://github.com/CABSEL/REDEMPTION/blob/master/logo.png" align="right"> 
REDEMPTION (REduced Dimension Ensemble Modeling and Parameter estimaTION) is a MATLAB toolbox for the identification of parameters and parameter ensembles of ODE models from time-series data. The toolbox is based on incremental parameter estimation (IPE) and integrated flux parameter estimation (IFPE) methods [1-3], in which the data fitting (parameter estimation) problem is formulated as a nested optimization of reduced dimension. REDEMPTION provides a user-friendly interface for model description (using Power-law, Lin-log kinetics or from SBML format), parameter estimation, ensemble modelling and visualization of results. For computational speed-up, the toolbox also offers a parallelization option using MATLAB Parallel Computing Toolbox. Please cite [4] if you use this toolbox.

## Required MATLAB toolboxes
[SPLINEFIT](http://ch.mathworks.com/matlabcentral/fileexchange/13812-splinefit?requestedDomain=true)Toolbox
[HYPERSPACE](http://www.ieu.uzh.ch/wagner/publications-software.html)

## Recommended third-party MATLAB toolboxes
- eSS [6] [MEIGO](http://gingproc.iim.csic.es/~gingproc/meigom.html) (MEtaheuristics for bIoinformatics Global Optimization) Toolbox with n_stuck option

- [SUNDIALS](https://computation.llnl.gov/projects/sundials) (SUite of Nonlinear and DIfferential/ALgebraic equation Solvers) [7]

- [MATLAB Parallel Computing Toolbox](https://ch.mathworks.com/products/parallel-computing.html) (only when parallelization is desired)

- To import model in SBML format: [SBML Toolbox](http://sbml.org/Software/SBMLToolbox) [4] and [LibSBML](http://sbml.org/Software/libSBML) [5] or [SimBiology](https://ch.mathworks.com/products/simbiology.html)

REDEMPTION was implemented and tested on MATLAB 2012a platform.
