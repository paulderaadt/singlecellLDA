# singlecellLDA
Reproduction of methods found in  " Predicting cell types in single cell mass cytometry data"
Notebooks train LDA classifier and predict celltypes on 6 datasets.

BMMC
AML
HMIS-1
HMIS-2
PANORAMA
MULTICENTER

AML and BMMC notebook classify and analyse in same notebook
Other notebooks are split into classifier & analysis notebook. Classifier writes results to file and analysis reads from file to 
reduce waiting time when you wish to view/change the analysis.
