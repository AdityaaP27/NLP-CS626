# CS 626 Assignment: NLP Techniques Implementation

This repository contains three implementations related to Natural Language Processing (NLP), focusing on Named Entity Recognition (NER) and Part-of-Speech (POS) tagging. Each assignment explores a different model or method.

## Contents

### 1. Named Entity Identification (NER) using SVM
- **File**: `NER SVM.ipynb`
- **Description**: Implements a Support Vector Machine (SVM) model for Named Entity Identification (NEI). 
- **Highlights**:
  - Feature extraction for text data.
  - SVM-based classification.
  - Evaluation metrics to assess performance.

### 2. POS Tagging using CRF
- **File**: `POS Tagging (CRF Based).ipynb`
- **Description**: Applies Conditional Random Fields (CRF) for POS tagging. Focuses on hyperparameter tuning to optimize performance.
- **Highlights**:
  - Sequence labeling with CRF.
  - Hyperparameter optimization for improved tagging accuracy.

### 3. POS Tagging using HMM
- **File**: `POS Tagging (HMM Based).ipynb`
- **Description**: Uses a Hidden Markov Model (HMM) to perform POS tagging, leveraging probabilistic modeling.
- **Highlights**:
  - Probabilistic sequence modeling.
  - Emission and transition probabilities for tagging.

## How to Use
1. Clone this repository.
2. Open the respective Jupyter notebooks to explore the implementations.
3. Follow the instructions and execute the cells to reproduce results.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required Python libraries: scikit-learn, CRF++/pyCRFsuite, NumPy, pandas, etc. (Install dependencies using `pip install -r requirements.txt` if provided).

## Acknowledgements
These assignments were completed as part of the CS 626 coursework to gain hands-on experience with classical NLP methods and models.
"""