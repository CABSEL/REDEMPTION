# REDEMPTION
Reduced Dimension Ensemble Modeling and Parameter Estimation
<img style = "float: right;" src = "https://github.com/CABSEL/REDEMPTION/blob/master/logo.png" align="right"> 
REDEMPTION (REduced Dimension Ensemble Modeling and Parameter estimaTION) is a MATLAB toolbox for the identification of parameters and parameter ensembles of ODE models from time-series data. The toolbox is based on incremental parameter estimation (IPE) and integrated flux parameter estimation (IFPE) methods [1-3], in which the data fitting (parameter estimation) problem is formulated as a nested optimization of reduced dimension. REDEMPTION provides a user-friendly interface for model description (using Power-law, Lin-log kinetics or from SBML format), parameter estimation, ensemble modelling and visualization of results. For computational speed-up, the toolbox also offers a parallelization option using MATLAB Parallel Computing Toolbox. Please cite [4] if you use this toolbox.

## Required MATLAB toolboxes
[SPLINEFIT](http://ch.mathworks.com/matlabcentral/fileexchange/13812-splinefit?requestedDomain=true) Toolbox
[HYPERSPACE](http://www.ieu.uzh.ch/wagner/publications-software.html)

## Recommended third-party MATLAB toolboxes
- eSS [6] [MEIGO](http://gingproc.iim.csic.es/~gingproc/meigom.html) (MEtaheuristics for bIoinformatics Global Optimization) Toolbox with n_stuck option

- [SUNDIALS](https://computation.llnl.gov/projects/sundials) (SUite of Nonlinear and DIfferential/ALgebraic equation Solvers) [7]

- [MATLAB Parallel Computing Toolbox](https://ch.mathworks.com/products/parallel-computing.html) (only when parallelization is desired)

- To import model in SBML format: [SBML Toolbox](http://sbml.org/Software/SBMLToolbox) [4] and [LibSBML](http://sbml.org/Software/libSBML) [5] or [SimBiology](https://ch.mathworks.com/products/simbiology.html)

REDEMPTION was implemented and tested on MATLAB 2012a platform.

## Last Update, Download & Installation
Current version: 07.08.2015

Download & unzip the [REDEMPTION.zip](https://github.com/CABSEL/REDEMPTION/blob/master/redemption.zip) file.

We welcome suggestions for additional features that you would like to see on REDEMPTION.

## License
Redistribution and use in P-code form is permitted provided agreeing to the [License](https://github.com/CABSEL/REDEMPTION/blob/master/License).

## References
1. Jia, G., G. Stephanopoulos, and Gunawan, R. Incremental parameter estimation of kinetic metabolic network models. BMC Systems Biology, 2012. 6: p. 142. [abstract](https://bmcsystbiol.biomedcentral.com/articles/10.1186/1752-0509-6-142)

2. Jia, G., G. Stephanopoulos, and Gunawan, R. Ensemble kinetic modeling of metabolic networks from dynamic metabolic profiles. Metabolites, 2012. 2(4): p. 891-912. [abstract](http://www.mdpi.com/2218-1989/2/4/891)

3. Liu, Y., and Gunawan, R. Parameter estimation of dynamic biological network models using integrated fluxes. BMC Systems Biology, 2014. 8: p. 127. [abstract](https://bmcsystbiol.biomedcentral.com/articles/10.1186/s12918-014-0127-x)

4. Liu, Y., Manesso, E. and Gunawan R. REDEMPTION: Reduced Dimension Ensemble Modeling and Parameter Estimation. Bioinformatics 31 (20): 3387-3389 (2015). [abstract](https://academic.oup.com/bioinformatics/article/31/20/3387/195825)

5. Zamora-Sillero, E., et al., Efficient characterization of high-dimensional parameter spaces for systems biology. BMC Systems Biology, 2011. 5: p. 142.

6. Egea, J.A., R. Marti, and J.R. Banga, An evolutionary method for complex-process optimization. Computers & Operations Research, 2010. 37(2): p. 315-324.

7. Hindmarsh, A.C., et al., SUNDIALS: Suite of nonlinear and differential/algebraic equation solvers. Acm Transactions on Mathematical Software, 2005. 31(3): p. 363-396.

8. Keating, S.M., et al., SBMLToolbox: an SBML toolbox for MATLAB users. Bioinformatics, 2006. 22(10): p. 1275-7.

9. Bornstein, B. J., Keating, S. M., Jouraku, A., and Hucka M. (2008) LibSBML: An API Library for SBML. Bioinformatics, 24(6):880–881.

## Acknowledgement
This work is supported by funding from Swiss National Science Foundation.
