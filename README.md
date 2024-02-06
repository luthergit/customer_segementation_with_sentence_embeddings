# Clustering with Sentence Embeddings

## Introduction

There are different ways to go about doing a customer segementation project, here I will be exploring three distinct ways and find the best:
* Kmeans
* K-Prototype
* Sentence Embeddings + Kmeans

**This project does not cover EDA or variable selection, which are important steps in this kind of project**

## Data 

The original data used in this project is from a public Kaggle dataset called "Banking Dataset - Marketing Targets" and can be found [here](https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets) 


For this project, we will focus on the first 8 columns of the dataset, which include:

* `age` (numeric)
* `job`: type of job (categorical)
* `marital`: marital status (categorical)
* `education`: education level (categorical)
* `default`: has credit in default? (binary)
* `balance`: average yearly balance in euros (numeric)
* `housing`: has a housing loan? (binary)
* `loan`: has a personal loan? (binary)

Inside the data folder, you'll find two CSV files: `train.csv` (the original training dataset) and `embedding_train.csv` (the dataset after performing an embedding, which will be explained later) using the `embedding_creation.py`.