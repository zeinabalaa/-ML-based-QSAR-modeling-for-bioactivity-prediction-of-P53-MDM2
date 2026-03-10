# QSAR Modeling of p53–MDM2 Inhibitors

This repository presents a computational workflow for building QSAR models to predict the activity of small molecules targeting the p53–MDM2 protein–protein interaction, an important target in anticancer drug discovery.

The project applies cheminformatics techniques and machine learning methods to analyze molecular structures and identify patterns associated with biological activity.

## Workflow

### 1. Data Collection and Curation
Bioactivity data were retrieved from the ChEMBL database and curated for modeling.

### 2. Feature Generation
Molecular representations were generated using Morgan fingerprints to capture structural features of the compounds.

### 3. Machine Learning Modeling
Two machine learning algorithms were applied for activity prediction:

- Random Forest  

- Support Vector Machine (SVM)

### 4. Clustering Analysis

K-Means clustering was used to explore structural similarity and group compounds with related structural patterns.

## Purpose

The goal of this project is to demonstrate how cheminformatics and machine learning approaches can be integrated to support computational drug discovery and predictive modeling.

## Tools and Libraries

- Python  
- RDKit  
- Scikit-learn  
- Pandas  
- NumPy
