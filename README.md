# Assessment of *SLC25A46* variants in idiopathic Parkinson’s disease

`GP2 ❤️ Open Science 😍`

[![DOI](https://zenodo.org/badge/920284062.svg)](https://doi.org/10.5281/zenodo.14715008)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


**Last Updated:** January 2025

## Summary
This repository contains all analyses for the manuscript titled ***"Assessment of SLC25A46 variants in idiopathic Parkinson’s disease"***. 

---

### Data Statement 
* Results were generated using
  - GP2 data release 6 (controlled-tier access; DOI: 10.5281/zenodo.10472143) 
  - GP2 data release 7 (controlled-tier access; DOI: 10.5281/zenodo.10962119)
  - AMP-PD v3.0 (controlled-tier access)


## Repository Orientation
```
analyses/
├── AMPPD
│   └── 00_SLC25A46_AMP-PD.ipynb
└── GP2
    ├── 00_SLC25A46_GP2_Genotyping_Imputed.ipynb
    └── 01_SLC25A46_GP2_WGS.ipynb
```

## Notebooks Description
| **Directory** | **Notebook**                             | **Description**                                             |
|:-------------:|:----------------------------------------:|:-----------------------------------------------------------:|
| AMPPD/        | `00_SLC25A46_AMP-PD.ipynb`                | Analyzes AMP-PD whole-genome sequencing data                |
| GP2/          | `00_SLC25A46_GP2_Genotyping_Imputed.ipynb` | Analyzes GP2 genotyped data across ancestries               |
|               | `01_SLC25A46_GP2_WGS.ipynb`                | Analyzes GP2 whole-genome sequencing data from EUR ancestry |


## Data Privacy
All individual-level data have been removed, including sample IDs and identifiers. Sensitive paths have been cleared. Notebooks have been saved as `.ipynb` files for easy sharing while ensuring compliance with data privacy standards.

## Software and Tools
|Software/Tool     |Version   |RRID                  |
|------------------|----------|----------------------|
|Python	           |3.9	      |RRID:SCR_008394       |
|Jupyter Notebook  |6.5	      |RRID:SCR_018315       |
|PLINK	           |1.9	      |RRID:SCR_001757       |
|PLINK	           |2.0       |RRID:SCR_001757       |
|ANNOVAR	   |2017Jul16 |RRID:SCR_012821       |
