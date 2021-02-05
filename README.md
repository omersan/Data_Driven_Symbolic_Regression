**In part1_eqation_discovery/stridge_eq_disc/ contains sparse Optimzation algorithm

>**Interpretable machine learning (symbolic regression) using Genetic programming/Gene expression programming and Sparse Optimization used to identify physical process, numerical schemes, and LES subgrid scale (eddy viscosity) turbulence models.**

# Abstarct:
In this study we put forth a modular approach for distilling hidden flow physics from discrete and sparse observations. To address functional expressiblity, a key limitation of the black-box machine learning methods, we have exploited the use of symbolic regression as a principle for identifying relations and operators that are related to the underlying processes. This approach combines evolutionary computation with feature engineering to provide a tool for discovering hidden parameterizations embedded in the trajectory of fluid flows in the Eulerian frame of reference. Our approach in this study mainly involves gene expression programming (GEP) and sequential threshold ridge regression (STRidge) algorithms. We demonstrate our results in three different applications: (i) equation discovery, (ii) truncation error analysis, and (iii) hidden physics discovery, for which we include both predicting unknown source terms from a set of sparse observations and discovering subgrid scale closure models. We illustrate that both GEP and STRidge algorithms are able to distill the Smagorinsky model from an array of tailored features in solving the Kraichnan turbulence problem. Our results demonstrate the huge potential of these techniques in complex physics problems, and reveal the importance of feature selection and feature engineering in model discovery approaches.

**The repository consits of three parts:**
1) Equation (PDE) Discovery using GEP and STRidge,
2) Trucation Error Analysis using GEP and STRidge,
3) Hidden Physics Discovery using GEP and LES sub grid scale Modelling using GEP and STRidge. 

**Genetic/Gene Expression Programming:**                                                                             
Chromosome |  GEP Flow chart
------------ | -------------
<img src="https://github.com/sayin/Data_Driven_Symbolic_Regression/blob/master/part4_results/figure1.png" width="350" height="300">| <img src="https://github.com/sayin/Data_Driven_Symbolic_Regression/blob/master/part4_results/figure2.png" width="350" height="300">

**Sparse Optimization:**              

<img src="https://github.com/sayin/Data_Driven_Symbolic_Regression/blob/master/part4_results/figure3.png" width="500" height="350" >

>**Hidden source term identified from sparse data collected from 2D vortex merger**.

 2D vortex meger | GEP 
------------ |------------ 
<img src="https://github.com/sayin/Data_Driven_Symbolic_Regression/blob/master/part4_results/figure33.png" width="450" height="350">| <img src="https://github.com/sayin/Data_Driven_Symbolic_Regression/blob/master/part4_results/figure34.png" width="350" height="300">

>**Smagorinsky eddy viscosity turbulence model  identified by GEP and Sparse regression along with ad-hoc (calibrated) parameter for 2D decaying trubulence**.

 GEP | Sparse regression | 2D decaying trubulence with identified SGS model
------------ |------------ | -------------
<img src="https://github.com/sayin/Data_Driven_Symbolic_Regression/blob/master/part4_results/figure35.png" width="350" height="300">|<img src="https://github.com/sayin/Data_Driven_Symbolic_Regression/blob/master/part4_results/figure36.png" width="350" height="300">| <img src="https://github.com/sayin/Data_Driven_Symbolic_Regression/blob/master/part4_results/figure37.png" width="350" height="300">



**Published Journals:**
1) Vaddireddy, H., Rasheed, A., Staples, A. E., & San, O. (2020). Feature engineering and symbolic regression methods for detecting hidden physics from sparse sensor observation data. Physics of Fluids, 32(1), 015113. (https://aip.scitation.org/doi/full/10.1063/1.5136351)

2) Vaddireddy, H., & San, O. (2019). Equation discovery using fast function extraction: A deterministic symbolic regression approach. Fluids, 4(2), 111. (https://www.mdpi.com/2311-5521/4/2/111)

# ACKNOWLEDGMENTS:
This material is based upon work supported by the U.S. Department of Energy, Office of Science, Office of Advanced Scientific
Computing Research under Award No. DE-SC0019290. O.S. gratefully acknowledges their support.
