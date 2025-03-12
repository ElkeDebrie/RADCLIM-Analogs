# RADCLIM-Analogs: High-Resolution Gridded Hourly Median Precipitation dataset for Belgium (1940-2016) Using the Analogue Technique

This repository holds a notebook describing how to find the analogs for a given date between the 1st January 1940 and the 31st December 2006 in the **RADCLIM-Analogs-median** dataset.

This dataset provides maps of the analogues median at 1 km resolution of the hourly accumulated precipitation over Belgium from 1940 to 2016. 
We used the analog technique to provide for every day in the past (1940 – 2016) the 25 best analogs selected from the high resolution RMI RADCLIM radar database that is available from 2017 to 2022. The median was then extracted from this ensemble.

This notebook is provided as supplementary material to the article:

* Debrie, E., Demaeyer, J., and Vannitsem, S.: Hourly precipitation series over Belgium based on the Analogue Technique, Earth Syst. Sci. Data Discuss. [preprint], doi:, in review, 2025.

Before running this notebook, the dataset must first be downloaded from the Zenodo platform (https://zenodo.org/records/14965711) and installed following the installation instruction available there.

## Running the notebook

The needed dependencies are detailed in the `environment.yml` file.
It allows one to easily create an [Anaconda](https://www.anaconda.com/) or a [Miniconda](https://docs.anaconda.com/miniconda/) environment:

    conda env create -f environment.yml

Then one just needs to run

    conda activate radclim-analogs
    jupyter-notebook

to be able to load the notebook.



