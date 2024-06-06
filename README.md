# Predicting-T-Cell-Receptor-Specificity

## Overview

This project is part of the University of Bristol MSc in Data Science as Industry project for Etcembly, focusing on predicting T-Cell Receptor (TCR) specificity. T cells are crucial for adaptive immunity, recognizing and eliminating infected or cancerous cells. TCRs, composed of alpha and beta subunits, are highly diverse and essential for a proper immune response. This project aims to analyze TCR repertoire data from the VDJdb and use machine learning techniques to predict TCRs that will bind to specific epitopes.

## Problem Statement

Predicting TCR specificity from sequence alone is a significant challenge in immunotherapy. The goal is to develop models that can classify TCRs based on their specificity to different epitopes, potentially transforming immunotherapies and personalized medicine.

## Data Source

The primary dataset for this project is the VDJdb, a comprehensive database of TCR sequences and their known specificities. You can download the VDJdb from [this link](https://vdjdb.cdr3.net/).

## Project Tasks

### 1. Data Download and Preprocessing
1.1 Download the zip file from GitHub and focus on the VDJdb.txt file.
1.2 Preprocess the dataset. Understand what each column represents and retain columns relevant to the project.

### 2. Addressing Limitations of One-Hot Encoding
Discuss the limitations of using one-hot encoding for TCR sequences and propose alternative methods considering CDR3 length distribution.

### 3. Distance/Similarity Matrix Calculation
Estimate a distance/similarity matrix for the alpha and beta chains separately, and for the combined alpha-beta chains. Tools like TCRDist, GLIPH, or GIANA can be used.

### 4. Dimensionality Reduction and Visualization
Plot TCRs in 2D using dimensionality reduction techniques (e.g., PCA, t-SNE, UMAP) and color them based on specificity. Compare the results for alpha, beta, and combined chains.

### 5. Clustering Analysis
Write code to cluster TCRs and evaluate how well they cluster based on specificity. Provide explanations for the clustering performance.

### 6. Predictive Modelling
Develop a model to predict antigen specificity from TCR sequences. Use any suitable supervised/unsupervised algorithm and comment on the model's performance.
