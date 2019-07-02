# fungal_gdm
GDM work for the 2018 WWPS soil survey data

This project contains the R Notebook (.Rmd) files for pre-processing and running a Generalized Dissimilarity Model for our Fungal OTU data. The pre-processing steps include normalizing sampling depth by (1) rarefraction and (2) relative abundance and outputs GDM-compatable files for both... except the gdm.varImp function throws errors if you try to use the relative abundance data. 

Error: Error in gdm.varImp(gdmTab, geo = T, splines = NULL, knots = NULL, fullModelOnly = F, : Response spTable has negative values. Must be between 0 - 1. 

