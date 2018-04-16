# Predicting exoplanet mass and radius relationship

Folder1 : BenchmarkingWRF16-result

Contains R code, data, outputs to produce Figure 1 and Figure 2 in the paper. 

Folder2: Kepler-code

Contains R code, data, outputs to produce the rest figures in the paper. 
 
-- Kepler.R: the main code.
-- MR_Kepler_170605_noanalytTTV_noupplim.csv: Kepler data
-- k2-planets.csv: K2 data
-- MainFunctions: the folder contains the following three functions:
		i) cross-validation.R: the function to choose optimal degree of Bernstein polynomials based on cross-validation method
		ii) MLE.R: the function to estimate weights in the Bernstein polynomials function
		iii) MRpredict.R: the function to obtain conditional and marginal densities from the joint M,R distribution
-- Result-Kepler: to produce figures presented in the paper, run the code: Kepler-plot.R 