# GARCH-SOFIX
This is the repository for R code associated with the paper "Forecasting Volatility of SOFIX Index with GARCH Models", submited to MDPI Journals in 2024 

Available R scripts
Filename	Description
01-01-Get_SOFIX.R	Using the internet, imports a dataset of prices of the SOFIX index.
02-Do_Descriptive_Figures_SOFIX.R	Creates and saves all descriptive figures presented in the paper.
03-Do_ARCH_and_Unit)Roots_Tests-Sofix.R	Performs the arch and unit roots tests in the data.
04-04-Estimate_SOFIX_5X6.R	Estimate an introductory Garch model and present results.
04-Estimate_BEST_SOFIX_2X2.R Estimate the BEST ARMA(1,1)-Garch(2,1) models and present results.
04-Estimate_BEST_SOFIX_2X2_2.R Estimate the BEST ARMA(1,1)-Garch(1,1) models and present results.
05-Find_Best_Garch_SOFIX_5x6.R	Finds the best sGarch/eGarch/gjrGarch/iGarch/csGARCH model for the dataset.
06-Simulation_Forecasts_SOFIX.R	Simulates the previous GARCH model and plots paths and probabilities.
