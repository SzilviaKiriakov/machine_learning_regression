# Machine learning models for a binary classification problem

This repository contains data and code to analyze a clinical dataset.
The data was downloaded from Kaggle. It contains clinical variables
associated with PCOS. The goal of the analysis is to build a
model that predicts PCOS from the clinical measurements.

The first notebook explores the data, the clinical variables and their
measurements. I found that only a single patient has missing measurements,
so this dataset is very well curated.

The second notebook aims to find the best model architectures to fine-tune
for this prediction task. Kaggle listed this dataset as a regression problem, 
but I found that the label (PCOS (Y/N)) requires binary classification.
