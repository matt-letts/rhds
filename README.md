# Reproducible health data science short course

This repository contains the code for the short course practical sessions. 
I have updated the readme to reflect the fact that we were working with a new branch, but then merged it

## Setup instructions

Use Conda / Mamba to create an R environment and then install the R packages from the installation script.

```
mamba env create -f environment.yml
Rscript install.r
```

## To run

```
bash download-data.sh
Rscript download-pan-cancer-clinical.r
```

## Directory set-up

Directory information in config-template.env file