# AgingHemaTopoMap

This repository contains the code used to generate the figures in the paper ["Spatial mapping of human hematopoiesis at single-cell resolution reveals aging-associated topographic remodeling".](https://doi.org/10.1182/blood.2023021280).

The code is written in python and uses the following packages:
* [numpy](https://numpy.org/)
* [scipy](https://www.scipy.org/)
* [pandas](https://pandas.pydata.org/)
* [matplotlib](https://matplotlib.org/)
* [seaborn](https://seaborn.pydata.org/)
* [anndata](https://anndata.readthedocs.io/en/latest/)
* [joblib](https://joblib.readthedocs.io/en/latest/)
* [statannotations](https://statannotations.readthedocs.io/en/latest/statannotations.html)

To install the packages, create new virtual environment and run the following command:
```bash
pip install -r requirements.txt
```

This will install the packages with the versions used in the paper.

## Data

Data to reproduce the figures is avaliable in associated [Zenodo project data](https://zenodo.org/records/10677544).

### Data files

* [data/NBM_dataset.h5ad](data/NBM_dataset.h5ad) - AnnData object containing the data used to generate the figures. To work with the dataset, download NBM_dataset.h5ad from Zenodo an put it into the data folder.
* [data/clinical_annotation.csv](data/clinical_annotation.csv) - Clinical annotation for the samples in the AnnData object.
* [data/platelets.xlsx](data/platelets.xlsx) - Platelet counts for the samples in the AnnData object.
* [data/Values_for_Panel_1F_correlations.xlsx](data/Values_for_Panel_1F_correlations.xlsx) - Values for the correlations in Figure 1F.

Main AnnData contains graph neural network embeddings for community detection stored in X and mean expression data in obs with suffix '_mean_intensity'. 

## Notebooks

The notebooks used to generate the figures are in the [notebooks](notebooks) folder. The notebooks are numbered in the order they should be run to reproduce the figures.
