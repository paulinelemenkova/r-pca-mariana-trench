# R Principal Component Analysis (PCA) — Mariana Trench

R script performing Principal Component Analysis (PCA) on the Mariana Trench bathymetric data to reduce dimensionality and reveal the dominant modes of variation, visualising the variables and observations in the space of the leading principal components.

## Related publication

Lemenkova, P. Statistical Analysis of the Mariana Trench Geomorphology Using R
Programming Language. Geodesy and Cartography 2019, 45(2), 57-84.

- DOI: https://doi.org/10.3846/gac.2019.3785
- figshare: https://doi.org/10.6084/m9.figshare.9762860
- HAL: https://hal.science/hal-02277500
- Zenodo: https://zenodo.org/record/3385005
- ISSN: 2029-6991 (Scopus)

(PCA is not a numbered figure in that paper; this repository is a companion multivariate-analysis visual using the same Mariana Trench data.)

## Script

- Script_PCA.R: reads Depths.csv, standardises the variables and computes the PCA (prcomp), then plots the variance explained (scree), variable loadings and observation scores (biplot / factoextra fviz_pca).

## Methods

- Principal Component Analysis: eigen-decomposition of the standardised correlation/covariance structure for dimensionality reduction.

## Data

- Depths.csv: depth observations along the Mariana Trench cross-section profiles.

## Requirements

- R (>= 3.5); packages: stats (prcomp), factoextra, ggplot2

## Author and citation

Polina Lemenkova — ORCID https://orcid.org/0000-0002-5759-1089

Cite: Lemenkova, P. Statistical Analysis of the Mariana Trench Geomorphology Using R Programming Language. Geodesy and Cartography 2019, 45(2), 57-84. https://doi.org/10.3846/gac.2019.3785

## License

MIT — see LICENSE (Copyright Polina Lemenkova).
