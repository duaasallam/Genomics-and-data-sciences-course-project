# Genomics-and-data-sciences-course-project
Identification Of Key Genes Associated With Perineural Invasion In Pancreatic Ductal Adenocarcinoma using Monte carlo feature selection , Icremental feature selection and support vector machine . 
# Feature Selection and Classification

This project focuses on feature selection using Monte Carlo methods and incremental feature selection (IFS) in combination with Support Vector Machines (SVM) and Random Forest classifiers. The goal is to identify key features in gene expression data for distinguishing pancreatic ductal adenocarcinoma patients with perineural invasion (PNI) from those without PNI.

## About

The project utilizes Monte Carlo feature selection to rank gene expression features based on their importance scores. It then employs IFS with SVM and Random Forest classifiers to evaluate the performance of different feature subsets in distinguishing patients with and without PNI. The dataset used is obtained from the Gene Expression Omnibus (GEO) repository (GSE102238).

## Requirements

- Python 3.x
- Required Python packages: NumPy, scikit-learn, GEOparse, matplotlib

## Installation

```bash
pip install -r requirements.txt
"" python
Install geoparse
