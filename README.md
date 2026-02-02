# Drug–Target Binding Prediction with Graph Neural Networks

## Overview
This project implements a Graph Neural Network (GNN) to predict drug–target binding interactions using molecular graph representations derived from SMILES strings. The work demonstrates how structure-aware deep learning can be applied to biological interaction prediction.

---

## Problem
Experimental screening for drug–target interactions is costly and slow. This project explores whether molecular graph representations combined with neural networks can capture meaningful patterns related to binding behavior.

---

## Approach
- Convert SMILES strings into molecular graphs (atoms as nodes, bonds as edges)
- Encode atom- and bond-level features
- Train a Graph Neural Network on drug–target pairs
- Evaluate performance using standard metrics

All data preprocessing, model training, and evaluation are contained within a single Jupyter notebook.

---

## Tech Stack
- Python
- PyTorch & PyTorch Geometric
- RDKit
- NumPy, pandas
- Jupyter Notebook

  
## Next Steps
- Incorporate protein sequence or structure embeddings
- Tune hyperparameters and add cross-validation
- Compare against baseline machine learning models


## Author
Jess  
Data Science / Computational Biology
