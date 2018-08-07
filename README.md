# Data Science and Big Data Overview Training
This repository contains Jupyter notebooks and associated data for the District Data Labs (DDL) introductory training on data science and big data.

## Requirements

Before running any code in this repository, make sure you have installed the requirements (preferably in a `virtualenv` or `conda` environment) with:

```
pip install -r requirements.txt
```

## Notebooks

This repository contains the following notebooks:

* `exploratory_data_analysis.ipynb`: a notebook demonstrating basic exploratory data analysis (EDA) techniques using Yelp and U.S. Census data
* `supervised_learning.ipynb`: a notebook demonstrating supervised learning techniques on baseball player statistics
* `data_collection.ipynb`: a notebook demonstrating data acquisition through webscraping public speeches by the U.S. Secretary of Defense
* `unsupervised_learning.ipynb`: a notebook demonstrating unsupervised learning (clustering) on the public speeches referenced above


## Data

This repository is self-contained: the relevant data for the notebooks is available in `/data`. There are a number of `.csv` files. Each of these files provenance is explained in the relevant notebook where it gets used.
