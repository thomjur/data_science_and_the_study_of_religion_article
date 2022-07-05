# Introduction

**Last Update: 5 July 2022**

This is the GitHub repository containing the code and the data for the article "Data Science and the Study of Religion: Analyzing the Use and Meaning of 'Religion' in English Tweets" (submitted to DHQ in July 2022).

The repository includes the following folders.

## Data

This folder contains the Twitter data sample analyzed and described in the article. The subfolder `raw` contains the raw Twitter data collected over several days and weeks. The folder `annotated` includes the annotated data. 

## Code

This folder contains the different Jupyter notebooks with the code used to acquire, clean, and analyze the data. The `TwitterAnalysis.ipynb` also includes the training of the deep learning models using [fastai](https://github.com/fastai/fastai). Please note that the code in the notebooks needs the data to be in the right path, meaning that you might need to change several variables before you can execute the code. Yet, this repo and the code is not supposed to be used by others, it rather serves as a documentation.

Most of the Jupyter notebooks were run with [Google Colab](https://colab.research.google.com/) to profit from the GPUs.

