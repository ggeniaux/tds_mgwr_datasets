# Top-Down Scale Approaches for Multiscale GWR  

This repository provides access to the **real-world dataset** used in:  

> Geniaux (2025), *Top-Down Scale Approaches for Multiscale GWR with Locally Adaptive Bandwidths*  

It includes an R Markdown file: **`tds_mgwr_data_github.Rmd`**, which:  
- Downloads the dataset from the [PySAL library](https://pysal.org/) website.  
- Replicates the estimations presented in the paper.
- a .Rdata file with all data in R format (**alldatsets.Rdata**)  

## Requirements  

To run the R Markdown file, you will need:  
- **R** (≥ 4.0)  
- **RStudio**  
- **Python** (if not already installed)  

## Installation  

Using a terminal console, create and configure the required Python environment with Conda:  

```bash
conda create --name py3.12 python=3.12
conda install --name py3.12 pandas
conda install --name py3.12 numpy
conda install --name py3.12 geopandas
conda install --name py3.12 pysal
conda install --name py3.12 libpysal
conda install --name py3.12 mgwr

## Usage

	1.	Open tds_mgwr_data_github.Rmd in RStudio.
	2.	Knit or run the file to automatically download the dataset and reproduce the results from the article.

