# Aging Brain project

## Folder structure

This is the public repository for "Aging desexualizes the Drosophila brain transcriptome".

* The Rmd/html notebook with the code is under `code/`.
* Raw data, along with Tissue Specificity data and other metadata, is under `data/`

## Clone this repository

To download the repository, install git and run:

`git clone https://github.com/urbfr20/aging_brain.git`

Otherwise, it is possible to download the repository from the browser by clicking on the green "Code" button, then "Download Zip"

## Installing the Conda environment

To reproduce the results in this work, install all necessary packages by downloading and setting up Miniconda [here](https://docs.conda.io/en/latest/miniconda.html).

Then, run the following command from the repository base folder:

`conda env create -f environment.yaml`

Followed by:

`conda activate aging_brain`

Then, open rstudio (or similar) from the environment prompt:

`(aging_brain):~/aging_brain$ rstudio code/Analysis.Rmd`

