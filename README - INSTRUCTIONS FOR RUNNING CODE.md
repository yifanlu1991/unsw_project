# MDS-Capstone-Group-F

The following six scripts have been provided in the GitHub repository:

 - eda_final.ipynb: script for the preliminary exploration of the data and includes the visualisations used in the EDA section of the report
 - bayesian_optimisation_nosolar_final.ipynb: bayesian optimisation script (no solar generation variable)
 - bayesian_optimisation_nosolar_final.ipynb: bayesian optimisation script (including the solar generation variable)
 - model_nosolar_final.ipnyb: LSTM model without the solar generation variable - uses the hyperparameters recommended by the bayesian optimisation
 - model_withsolar_final.ipnyb: LSTM model with the solar generation variable - uses the hyperparameters recommended by the bayesian optimisation
 - analysis.ipynb: compares the prediction outputs from the models and calculates various metrics used in the analysis/discussion sections of the report
 
 In order to successfully run the scripts above, perform a git pull to retrieve all the files within the repository. 
 
 Once all the files have been retrieved, double check to ensure that all files are present and in the same folder (the scripts will not work if the data files are not in the same folder as the .ipynb script files). 
 
 Run the scripts with preferred IDE.
 
 More specific line-by-line commentary has been provided within each script. Please reference this for further context regarding how each script has been built.