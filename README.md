# duckdb_experiments
This repository contains my work with DuckDB and the experiments I run on DuckDB. The repository contains a data folder where we are supposed to have the datasets. The code is in the form of Jupyter notebooks.
Please refer to the accompanying blog here - https://learn2infiniti.com/experimenting-with-duckdb/. You can find more details about this repository in the blog.

### Datasets

Following datasets are used in the analysis so far:
1. Anime dataset - https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset
2. Bitcoin 1 second dataset Part 1 - https://www.kaggle.com/datasets/tzelal/binance-bitcoin-dataset-1s-timeframe-p1/data
3. Bitcoin 1 second datset Part 2 - https://www.kaggle.com/datasets/tzelal/binance-bitcoin-dataset-1s-timeframe-p2

Because of the size of the datasets, I have not added the datasets to the data folder. Please download the datasets from the above kaggle locations and add them to data folder after unzipping the folders. The code works with unzipped csv files.

### Jupyter notebooks and datasets usage
There are four jupyter notebooks.
1. DuckDB - Anime dataset
2. Pandas Anime dataset
3. DuckDB - Bitcoin dataset
4. Parquet vs DuckDB

Note the dataset and their usage in the respective jupyter notebooks below.
1. Anime dataset is used in DuckDB - Anime dataset and Pandas Anime dataset jupyter notebooks.
2. Bitcoin 1 second dataset Part 1 is used in DuckDB - Bitcoin dataset notebook
3. Bitcoin 1 second datset Part 2 along with Bitcoin 1 second dataset Part 1 is used in Parquet vs DuckDB

DuckDB - Anime dataset and Pandas Anime dataset run the same analysis on the anime datasets, one using DuckDB and the other using Pandas respectively. This is done to compare the performance of DuckDB with Pandas.

DuckDB - Bitcoin dataset jupyter notebook uses the DuckDB to moving averages on the Bitcoin second granularity dataset.

Parquet vs DuckDB computes technical indicators on the bitcoin datasets. Both the part1 and part2 of the bitcoin dataset are combined and the analysis is done on the combined dataset. Then a comparison is done between using parquet file and native DuckDB table format.

### Blog Posts
There are two accompanying blog posts to explain more about the tests that were performed.
1. DuckDB - Exploring and Experimenting - https://learn2infiniti.com/experimenting-with-duckdb/. This blog focuses on explaining the details in the first three jupyter notebooks.
2. Parquet and DuckDB - Analyzing large datasets -  This blog focuses on explaining the details in the `Parquet vs DuckDB` notebook.



