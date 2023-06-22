README

Imputed 2020 and 2021 CMI-PB data using inputs from:
https://github.com/joreynajr/cmi-pb-multiomics/tree/main/results/main/cmi_pb_datasets/processed/harmonized

All data is structured as subjects x features

22 subjects removed from 2020 data as they were missing RNASeq

Imputation was performed using the MICE* algorithm

RNASeq and abtiters were log2(x+1) transformed prior to imputation.

Contact: Anna Konstorum (anna.konstorum@yale.edu)

*Buuren S van, Groothuis-Oudshoorn Karin. mice: Multivariate imputation by chained equations in r. J Statist Softw. 2010; 1–68.
Vignette: https://cran.r-project.org/web/packages/miceRanger/vignettes/miceAlgorithm.html
