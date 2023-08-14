# DSN Bootcamp 2023

This repository contains material for producing analytics presented during the 2023 DSN Bootcamp. It contains Jupyter notebooks, with the code written in the Python language.

## Running the notebooks

### Locally using conda
To be able to run the notebooks on your local machine, you will first need to do the following (these instructions assume that you have [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/) installed):
1. Clone this repository  
2. Create a `conda` environment to be able to run the notebooks, using `environment.yml` to install the required libraries.   

You can run the following in a `bash` shell (or a git-bash terminal on Windows) to set everything up (in the folder your terminal is currently located):

```bash
git clone https://github.com/Flowminder/DSN_Bootcamp_2023
cd DSN_Bootcamp_2023
conda env create -f environment.yml
```

### Start working with the notebooks
To run the notebooks on your local machine, you can do the following:

1. Activate the `geo_python` environment you previously created using `environment.yml`  
2. Start a Jupyter Lab session  

To do this, you can run the following in a `bash` shell (or a git-bash terminal on Windows):

```bash
conda activate geo_python
jupyter lab
```

## Practical 1: Assessing health facilities coverage for maternal healthcare using GRID3 population estimates in Kaduna state

Using geospatial data:
- Population data for women aged 15-49
- Ward and state boundaries
- Health facility locations

We want to assess health facility coverage for maternal healthcare in Kaduna state, Nigeria.

## Practical 2: XXX


## Links
You can find a rendered version of the notebook for [Practical 1 here](https://nbviewer.org/github/Flowminder/DSN_Bootcamp_2023/blob/main/DSN_Bootcamp.%201.%20Assessing%20Health%20Facilities%20Coverage.ipynb).  
You can find a rendered version of the notebook for [Practical 2 here](https://nbviewer.org/github/Flowminder/DSN_Bootcamp_2023/blob/main/DSN_Bootcamp.%202.%20CDR%20analytics.ipynb).
