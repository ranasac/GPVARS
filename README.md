# GPVARS
Assisted History Matching and Uncertainty Quantification using Gaussian Processes Proxy Model and Variogram Based Sensitivity Analysis.

The full CMG data set for PUNQ-S3 reservoir case study is uploaded in the folder "PUNQ_S3.zip". There is a "Readme.docx" to guide users on how to open and run this data set in CMG IMEX software. The user must have a valid license of CMG in order to run this numerical simulation file. 

The code for GP_VARS and all necessary function codes are provided in the folder named "GP_VARS_code_Github.zip". There is a "Readme.docx" file in this folder in order to obtain detailed instructions of how to use this code.

In this code, we have not provided any reservoir case study since running them will require use of full license of CMG numerical simulator. However, the numerical simulation files and all other data including results are provided in a folder named “PUNQ_S3”. These datasets are also available at https://sites.psu.edu/gpvars/
Hence, we are providing 2 examples including the research paper example and a benchmark optimization function below which does not need any other external software other than Matlab in order to illustrate the use of this “gpvars_main” code. By following these steps, the user will know how to use “gpvars_main” code to their own problem.
This folder contains all the files needed to carry out a history match study using GP-VARS technique. However, the following pre-requistes must be completed before running these codes:
1)	This code has been ran and tested on Matlab 2015a. We believe the newer versions should be able to run the code without issues. However, older versions might throw some errors.
2)	Please download GPML matlab package in order to be able to train a Gaussian process model. The code is available for public download at this website: http://www.gaussianprocess.org/gpml/code/matlab/doc/
3)	Please download Variogram matlab function package in order to calculate experimental variogram to perform VARS sensitivity analysis. The code is available at: http://www.mathworks.com/matlabcentral/fileexchange/20355-experimental--semi---variogram?focused=3774679&tab=function

For more information, please follow the instructions in Readme.docx file. 
