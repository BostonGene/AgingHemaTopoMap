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

Data to reproduce the figures is avaliable in the [data](data) folder.

## Notebooks

The notebooks used to generate the figures are in the [notebooks](notebooks) folder. The notebooks are numbered in the order they should be run to reproduce the figures.
