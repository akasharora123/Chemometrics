## Chemometric methods for spectroscopy data analysis
---

## Overview
Chemometric analysis is the applicaiton of multivariate statistics and applied mathematics methods to chemical characeterization data to get insights such as examining quality/adulterants, identifying key chemical structures, or classifying/discriminating different varieties. Chemicals are commonly characterized by spectroscopy techniques such as mid-infrared or Fourier-transform infrared, which represents a series of intensities measured at different wavelengths. Most often, the intensities at different wavelengths are highly correlated, and many time the number of samples collected (data points) are less than the number of wavelengths (variables). Because of these two problems, the dimensionality reductions techniques (PCA and LDA) are the primarily used to project the data into a set of independent latent variables. 

## Examples in this work

- Coffee variants: Infrared spectrum of two types of coffee, Arabica and Robusta, are measured by  Downey *et al.* (*J. Agric. Food. Chem.* 1997, 45, 4357-4361). Using LDA, the two variants of coffee are differentiated along the LDA vector direction.
- Geographic origin of olive oils: PCA and LDA are applied on the measured infrared spectrum of olive oils which helps clusterinng them in latent-vector space, and thereby helps identifying the country of origin for different varieties. Data source: Tapp *et al., J. Agric. Food Chem.*, Vol. 51, No. 21, 2003.


## Prerequisites

- Python
- NumPy
- Pandas
- Seaborn
- MatplotLib
- Scikit-learn

