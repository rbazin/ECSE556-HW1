# Machine Learning Techniques for Transcriptomic Data Analysis

The goal of this homework is to study _transcriptomic data_ (expression of thousands of genes), corresponding to hundreds of cell lines, using multiple regression and clustering Machine Learning techniques.

All the code necessary to reproduce the results of the report can be run from the `notebook.ipynb` file.

Prior to running the code, you'll need to create a folder called `data`, containing the csv files of the features and labels : `gdsc_expr_postCB.csv` and `gdsc_dr.csv`.

A `requirement.txt` is provided to reproduce the python (version 3.11.4) environment used.

`nested_scores.pkl` contains the results of the nested cross validation hyperparameter optimization for the LASSO regression model.

This project was part of the ECSE556 : Deep Learing for Biology course, at McGill University.
