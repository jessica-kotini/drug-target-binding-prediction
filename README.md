# Drug–Target Binding Prediction with Graph Neural Networks

## Overview
This project explores predicting drug–target binding interactions using a Graph Neural Network (GNN). Small-molecule drugs are represented as molecular graphs derived from SMILES strings, enabling structure-aware learning beyond traditional fingerprint-based methods.

The goal is to demonstrate how graph-based deep learning can be applied to biological interaction prediction.

## Problem
Experimental screening for drug–target interactions is expensive and time-consuming. This project investigates whether molecular graph representations combined with neural networks can learn meaningful patterns related to binding behavior.

## Data
- Drug molecules represented as **SMILES strings**
- SMILES converted to **graph structures** (atoms as nodes, bonds as edges)
- Binding labels provided per drug–target pair

> Only data samples are included. Full datasets are excluded due to size.


## Method
1. Parse SMILES into molecular graphs  
2. Encode atom- and bond-level features  
3. Train a Graph Neural Network on drug–target pairs  
4. Evaluate model performance using standard metrics  

The full workflow is implemented in a Jupyter notebook.


## Results
- Successfully constructed molecular graphs from SMILES
- Implemented an end-to-end GNN training pipeline
- Results suggest graph-based representations capture relevant chemical structure information


## Tech Stack
- Python  
- PyTorch & PyTorch Geometric  
- RDKit  
- NumPy, pandas  
- Jupyter Notebook  


'''## Project Structure
notebooks/   # Model development and experiments
data/        # Data (not included or lightly sampled)
results/     # Outputs and figures
'''


---

## Next Steps
- Incorporate protein sequence or structure embeddings  
- Perform hyperparameter tuning and cross-validation  
- Compare against baseline ML models  

---

## Author
Jess  
Data Science / Computational Biology

