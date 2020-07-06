# Chemometric Analysis

Chemometric analysis is the applicaiton of multivariate statistics methods to chemical characterization data to get insights about the quality/adulterants present or to classify different varieties of chemicals. Chemicals are commonly characterized by spectroscopy techniques such as mid-infrared or Fourier-transform infrared spectroscopy, which represents a series of intensities measured at different wavelengths. Typically, the intensities at different wavelengths are highly correlated, and many often the number of samples collected (data points) are less than the number of wavelengths (variables). Because of these two problems, the dimensionality reductions methods (PCA and LDA) are primarily used to project the data into independent-latent-variables space. Visualizing the data on 2- or 3-dimensions latent-variable space help identifying important features. For predictive modeling, regression based on dimensionality-reduction, such as PCR-regression and PLS-regression are often used.     

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

## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
