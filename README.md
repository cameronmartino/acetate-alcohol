
Data and code from analysis of `Acetate reprograms gut microbiota during alcohol consumption`.

### Repository Structure

* code

This directory contains the code (as notebooks) for each step in a numerically organized format. More descriptions can be found within the README file for that directory.

* data

This directory contains the input data, along with some output from computationally expensive tools. 

* results

The main and extended figures and tables from the paper which can be reproduced by running the notebooks within the `code` directory.

### Setup

There are two options for setup to run the notebooks.

The first option is a QIIME 2019.10 environment amended with any additional plugins. This option is preferable for `OSX` users. The conda yml file is provided in `environment/conda-environment.yml`. Installation of the environment can be done through `conda env create -n acetate-alcohol-env --file environment/conda-environment.yml`.

With the environment installed and activated each notebook can be run and populate the `results` directory with all of the extended tables and figures used in the paper.