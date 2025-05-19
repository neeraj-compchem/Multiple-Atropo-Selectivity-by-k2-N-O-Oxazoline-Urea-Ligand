# Multiple-Atropo-Selectivity-by-k2-N-O-Oxazoline-Urea-Ligand
This is a data and code repository for the following manuscript:<br>
"Multiple Atropo Selectivity by <i>κ</i><sup>2</sup>-<i>N</i>,<i>O</i>-Oxazoline Urea Ligands in Cobaltaelectro-Catalyzed C–H Activations: Decoding Selectivity with Data Science Integration".


Last updated on Mar 19, 2025

## Overview

### Python Files
- **forward_stepwise.py**  
  - Multivariate model searching function using the stepwise forward feature selection method.

### Notebooks
- **pca_ligand_class.ipynb**  
  - Principal component analysis (PCA) with all the collected features.
  - Deconstructed PCA with categorized features.

- **mvlr_modeling_and_extrapolation.ipynb**  
  - MVLR modeling and sorting.  
  - Prediction performance visualization.  
  - Model extrapolation with an external set.

 
# Packages requirements
The following packages were present during code development in the Jupyter notebooks. It is recommended to use the same versions while reproducing the results.
```
python = 3.12.4
numpy = 1.26.4  
pandas = 2.2.2 
scipy = 1.13.1 
sklearn = 1.4.2
matplotlib = 3.8.4
mpl_toolkits (matplotlib) = 3.8.4
seaborn = 0.13.2   
```

## How to cite
The code provided here is released under the MIT license. Commercial use, modification, and private use are all permitted. Please use the following citation to acknowledge this work:

```
@article{https://doi.org/10.1002/ceur.202500071,
author = {Boos, Philipp and Pandit, Neeraj Kumar and Dana, Suman and von Münchow, Tristan and Hashidoko, Airu and Haberstock, Laura and Herbst-Irmer, Regine and Stalke, Dietmar and Ackermann, Lutz},
title = {Multiple Atropo Selectivity by κ2-N,O-Oxazoline Urea Ligands in Cobaltaelectro-Catalyzed C─H Activations: Decoding Selectivity with Data Science Integration},
journal = {ChemistryEurope},
volume = {3},
pages = {2500071},
doi = {https://doi.org/10.1002/ceur.202500071},
url = {https://chemistry-europe.onlinelibrary.wiley.com/doi/abs/10.1002/ceur.202500071},
eprint = {https://chemistry-europe.onlinelibrary.wiley.com/doi/pdf/10.1002/ceur.202500071},
year = {2025}
}
```
