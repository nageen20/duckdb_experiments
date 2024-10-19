# duckdb_experiments
This repository contains my work with DuckDB and the experiments I run on DuckDB. The repository contains a data folder where we are supposed to have the datasets. The code is in the form of Jupyter notebooks.
Please refer to the accompanying blog here - https://learn2infiniti.com/experimenting-with-duckdb/. You can find more details about this repository in the blog.
Following datasets are used in the analysis so far:
1. Anime dataset - https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset
2. Bitcoint 1 second dataset Part 1 - https://www.kaggle.com/datasets/tzelal/binance-bitcoin-dataset-1s-timeframe-p1/data

Because of the size of the datasets, I have not added the datasets to the data folder. Please download the datasets from the above kaggle locations and add them to data folder after unzipping the folders. The code works with unzipped csv files.

There are three jupyter notebooks.
1. DuckDB - Anime dataset
2. Pandas Anime dataset
3. DuckDB - Bitcoin dataset

DuckDB - Anime dataset and Pandas Anime dataset run the same analysis on the anime datasets, one using DuckDB and the other using Pandas respectively. This is done to compare the performance of DuckDB with Pandas.

DuckDB - Bitcoin dataset jupyter notebook uses the DuckDB to moving averages on the Bitcoin second granularity dataset.
