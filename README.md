This repository contains the code which can generate the figures shown in the paper.

<img width="283" height="102" alt="image" src="https://github.com/user-attachments/assets/d7338a52-15c1-486c-b6df-64fddab53e20" />


The following libraries are required to run the code:
Scikit learn
Numpy
Scipy
Pyomo
Ipopt optimization solver
Tensor flow
Matplotlib
Each code file corresponds to an image and analysis performed in the results and discussion section:

## Synthetic time-resolved process Raman data generation

**Gen_Raman_processes** : This jupyter notebook shows how the synthetic Raman process data is constructed and has the code which generates figure 2

**Generate_training_data** : This jupyter notebook creates the synthetic Raman process data for the three axis explored :- (i) Scenarios 1-3, (ii) Inhibition strength, and (iii) Spectral overlap and saves it in the Train Conditions sub-directory

## Coupled Raman Hybrid Models

**CRHM_SC1_2** : This jupyter notebook solves the coupled Raman hybrid model for scenarios 1 and 2 and saves them in the Coupled Performance/Hybrid model sub-directory

**CRHM_SC3** : This jupyter notebook solves the coupled Raman hybrid model for scenarios 3 and saves them in the Coupled Performance/Hybrid model sub-directory

## Iterative Raman Hybrid Models

**IRHM_SVD_SC1_2** : This jupyter notebook solves the iterative Raman hybrid model with SVD initialization for scenarios 1 and 2 and saves them in the Iterative Performance/SVD_init sub-directory

**IRHM_SVD_SC3** : This jupyter notebook solves the coupled Raman hybrid model with SVD initialization for scenarios 3 and saves them in the Iterative Performance/SVD_init sub-directory

**IRHM_SML_SC1_2** : This jupyter notebook solves the iterative Raman hybrid model with SIMPLISMA initialization for scenarios 1 and 2 and saves them in the Iterative Performance/SIMPLISMA_init sub-directory

**IRHM_SML_SC3** : This jupyter notebook solves the coupled Raman hybrid model with SSIMPLISMA initialization for scenarios 3 and saves them in the Iterative Performance/SIMNPLISMA_init sub-directory

## Coupled Raman Mechanistic Models

**CRMMv1_SC1_2** : This jupyter notebook solves the coupled Raman mechanistic model 1 (Eq.5-7) for scenarios 1 and 2 and saves them in the Coupled Performance/Mechanistic model - v1 sub-directory

**CRMMv1_SC3** : This jupyter notebook solves the coupled Raman mechanistic model 1 (Eq.5-7)for scenarios 3 and saves them in the Coupled Performance/Mechanistic model - v1 sub-directory

**CRMMv1_SC1_2** : This jupyter notebook solves the coupled Raman mechanistic model 1 (Eq.8-10) for scenarios 1 and 2 and saves them in the Coupled Performance/Mechanistic model - v2 sub-directory

**CRMMv1_SC3** : This jupyter notebook solves the coupled Raman mechanistic model 1 (Eq.8-10)for scenarios 3 and saves them in the Coupled Performance/Mechanistic model - v2 sub-directory

## Methods and Models performance and time comparison

**Performance_comparison** : This jupyter notebook imports all the pickled performances for all the different curve resolution methods and models and generates Figure 3- 5 from the paper

**Time_comparison** : This jupyter noteboook imports all the pickled wall clock times for all the different curve resolution methods and models
