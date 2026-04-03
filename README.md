# Macro Density Analysis: Nutritional Structure Exploration

This project investigates the latent structure of food nutrition using multivariate statistical modeling and unsupervised learning techniques.
Rather than analyzing nutrients independently, it treats nutrition as a high-dimensional space and studies its geometric and statistical properties.

---

## Features (Current Phase)

- End-to-end statistical analysis of nutritional data  
- PCA-based dimensionality reduction  
- Unsupervised clustering of food patterns  
- Structural interpretation of nutritional space

---

## Research Objective

This project investigates:
- Can foods be grouped by nutritional density patterns?  
- What latent dimensions define food composition?  

Rather than analyzing nutrients independently, this study treats nutrition as a structured high-dimensional space.
   
---

## Analytical Architecture Overview

The analysis is structured as a layered statistical workflow:

Raw Nutritional Data
- Data Cleaning & Normalization
- Distribution Modeling
- Correlation Structure Analysis
- PCA (Dimensionality Reduction)
- Nutritional Pattern Clustering
- Structural Interpretation

---

## Methodological Rationale

The analytical methods are selected to uncover the latent structure of nutritional data.

- Principal Component Analysis (PCA) is used to:
  - reduce dimensionality
  - identify latent nutritional axes
  - remove redundancy from correlated variables

- K-Means clustering is used to:
  - identify natural groupings in the reduced feature space
  - provide interpretable food segmentation based on the center of mass
 
This combination enables both structural decomposition and pattern discovery within the nutritional space.

---

## Technical Design

**Language:** Python  
**Environment:** Jupyter Notebook  

### Dataset
  - Source: USDA Food Composition Dataset
  - ~7,000 food items
  - 14 nutritional attributes

---

## Research Pipeline

This project follows a structured analytical workflow to uncover the latent structure of nutritional data:
### 1. Data Preparation
   Cleaning, validation, and normalization to ensure statistical consistency
### 2. Distribution Analysis
   Modeling nutrient distributions and identifying skewness and variance patterns
### 3. Correlation Structure Modeling
   Analyzing dependencies between nutrients and detecting redundant dimensions
### 4. Dimensionality Reduction (PCA)
   Extracting latent nutritional axes and defining the geometry of the feature space
### 5. Pattern Discovery (Clustering)
   Grouping foods into distinct nutritional clusters in the reduced space
### 6. Structural Interpretation
   Interpreting clusters as nutritional archetypes and synthesizing global structure

---

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Summary

This project is not just exploratory analysis.
It is a **structured, research-oriented statistical investigation** into the geometry of food nutrition.

---

## Practical Implications
The identified nutritional structure and archetypes can be directly applied to:

- Food categorization based on nutritional similarity
- Designing balanced meal templates
- Guiding food substitution strategies in diet planning
- Serving as structured input for automated meal planning systems

These applications bridge statistical analysis with real-world nutritional decision-making.

---

## Why This Matters

Understanding nutritional structure at a multivariate level enables:
- Systematic food categorization
- Data-driven nutrition planning
- Optimization-ready macro modeling
- Transparent decision logic for automated meal systems

---

## Notebook

[View full analysis notebook](https://github.com/lasombra7/macro-density-analysis/blob/main/notebooks/macro-density-analysis.ipynb)
