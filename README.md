# SmartCart Clustering System

A customer-segmentation project that applies clustering techniques to identify meaningful customer groups and support data-informed engagement strategies.

## Overview

This repository contains the complete SmartCart clustering project: the analysis notebook, source dataset, and supporting project documentation. The workflow prepares customer data, explores the features used for segmentation, and interprets the resulting customer groups.

## Repository Contents

| File | Description |
| --- | --- |
| `smartcart.ipynb` | End-to-end data preparation, exploration, clustering, and segment-characterization workflow. |
| `smartcart_customers.csv` | Customer dataset used by the notebook. |
| `SmartCart Clustering System.pdf` | Project report and supporting documentation. |
| `requirements.txt` | Python packages needed to run the notebook. |
| `DATASET.md` | Dataset scope, intended use, and privacy guidance. |

## Getting Started

1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Start Jupyter Notebook or JupyterLab:

   ```bash
   jupyter notebook
   ```

5. Open `smartcart.ipynb` and run the cells in order.

## Analysis Workflow

The notebook covers:

- Data cleaning and missing-value handling
- Feature engineering and outlier treatment
- Categorical encoding and feature scaling
- PCA-based visual exploration
- Cluster selection with elbow and silhouette analysis
- K-Means and agglomerative clustering
- Customer-segment characterization, including income and spending patterns

## Data Use

The dataset is provided for this project only. It includes demographic and financial-behavior attributes, so please confirm that public sharing is permitted before redistributing or reusing it. See [DATASET.md](./DATASET.md) for additional guidance.

## Documentation

For the detailed system description, methodology, and results, see [SmartCart Clustering System.pdf](./SmartCart%20Clustering%20System.pdf).
