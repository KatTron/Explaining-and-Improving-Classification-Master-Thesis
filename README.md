## Introduction

This repository contains the code for the analysis presented in my master thesis, "Exploration of Clustering for Explaining and Improving Classification". The project involves case studies clustering and classification methods to enhance understanding.

## Repository Structure

The main folder, Handin, contains three subfolders: Datasets, Explaining Classification, and Improving Classification.

## Datasets

The Datasets folder contains CSV files with the datasets for the diabetes and water quality datasets. The adult dataset is directly extracted within the Python files.

### Explaining Classification

The Explaining Classification folder includes the code for the three case studies discussed in Chapters 4, 5, and 6. This folder contains:

    distributions: This is an example file demonstrating how histograms showing overlap degrees were created.
    Three subfolders, each corresponding to a case study. Each subfolder contains the following three files:
        X purity: This file contains the code for creating clusters, calculating cluster purities, generating SHAP values, and creating Error Analysis Trees.
        X plots: This file contains the code for generating pairwise scatterplots.
        X f1: This file explains how the global F1 score was calculated.

### Improving Classification

The Improving Classification folder contains two files that detail the application of my method using bootstrapping and a single Random Forest (RF) classifier.

## Contact Information

For questions or support, please contact me at katharinatronier@gmail.com.

## Acknowledgements

I would like to thank my advisor, colleagues, and everyone who supported me throughout this project.
