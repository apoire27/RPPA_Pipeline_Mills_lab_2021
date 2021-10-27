This folder is used to create the RPPA Reports that SMART requests most of it is automated but several scripts require the user to make some hard code changes.
Most of these are to set up the desired patient samples that the user wishes to investigate more closely. 

All input data should be places into the imputs folder before attempting to run the scripts. 
There are backups of some of the necessary files in the permanent_files sub folder incase they were accidentally removed. 
The outputs folder should be emptied prior to each use as well to avoid overwriting files. 

NOTE: While most of the data outputs will not overwrite eachother this is not true for the graphs and as such the graphs should be moved after running to avoid over righting them. 


The order to run the scripts is as follows. 
	-Cleaner (THIS WILL NEED TO BE RUN IF YOUR DATA IS NOT IN THE CORRECT FORMAT CHECK DATA BEFORE ENTERING ANYTHING INTO THE PIPELINE) 
	-Pathway_Score_calculator.ipynb
	- Score_Caluclator.Rmd (eventually this will be encorporated into the Pathway_Score_calculator.ipynb)
	-Pathway_Score_calculator.ipynb
	-Pathway_prepare_Density_maper.Rmd
	-Heat_mapper.Rmd
	-RPPA_Report.Rmd
