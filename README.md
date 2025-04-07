# Survival of the littlest: Navigating sepsis diagnosis beyond inflammation in preterm neonates
This repository contains the R script, input files, and documentation required to reproduce the analysis and figures presented in our manuscript. In this study, we performed targeted metabolomics to profile amines and signaling lipids in 235 plasma samples obtained from preterm neonates to elucidate the pathophysiology of late-onset sepsis and identify biomarkers to accurately distinguish sepsis from non-infectious systemic inflammation. 


## Structure of repository

```
|-Data
	|-Amines_Data.xlsx 
	|-High_Data.xlsx 
	|-Low_Data.xlsx 
|-MetaData for Publication.xlsx 
|-MetaData Dictionary.xlsx
|-Metabolite Information Publication.xlsx
|-Oxylipin Information Publications.xlsx
|-Use Names List.xlsx
|-Script
	|-MOMETA Publication Final.Rmd
```

## Contents of files
Amines_Data: contains area ratios of amines
High_Data: contains area ratios of signaling lipids measured in the high pH assay
Low_Data: contains area ratios of signaling lipids measured in the low pH assay
MetaData for Publication: contains the metadata of 235 samples, such gestational age, birthweight, postnatal age, sample origin, and clinical biomarker levels	
MetaData Dictionary: contains detailed information about the MetaData for Publication columns
Metabolite Information Publication: contains mapping information about the reported metabolites and their categories and sub categories
Oxylipin Information Publications: contains information about precursors and enzymes involved in the formation of the reported oxylipins to generate biologically pertinent metabolite ratios
Use Names List: contains mapping information of internally named metabolites and publication-ready names
MOMETA Publication Final: contains the complete analysis pipeline to reproduce all analyses and figures presented in the manuscript
