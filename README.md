# Unsupervised and Supervised Methods for Predicting Optoelectronic Properties of Candidate Molecules for Organic Photovoltaic Applications

## Project Overview

This repository contains the implementation of our research project for CHEMENG277.  

Our study explores machine learning-based approaches for predicting key optoelectronic metrics: HOMO-LUMO gap and spectral overlap, using easily extractable chemical features. By leveraging unsupervised (K-Means clustering, PCA) and supervised learning (neural networks), we demonstrate that machine learning models can significantly reduce computational costs associated with Density Functional Theory (DFT) calculations.

## Repository Structure

- **`Project Code.ipynb`**: Jupyter Notebook containing the full implementation, including intermediate results, data preprocessing, feature extraction, model training, and evaluation.
- **`smiles_train.csv`**: Training dataset containing molecular SMILES strings and associated features.
- **`smiles_valid.csv`**: Validation dataset used for model evaluation.
- **`smiles_test.csv`**: Test dataset used to assess final model performance.
- **[Paper Link](https://docs.google.com/document/d/1cgpYhfUGrXe7-K0WmqduTYuskYvJ0pTrhX8rY3Lp6ys/edit?usp=sharing)**: Link to our full paper.

## Running The Code

To run the code, download the training, validation, and test datasets as well as the Project Code notebook. For all functions to work properly, please be sure to install the following Python packages in your local environment using the corresponding commands:
- Pandas: pip install pandas
- Numpy: pip install numpy
- RDKit: pip install rdkit-pypi
- Scikit-learn: pip install scikit-learn
- SciPy: pip install scipy
- Seaborn: pip install seaborn
- MatPlotLib: pip install matplotlib

Alternatively, these can be downloaded using Conda or Homebrew. While not strictly necessary, it is best to run each code cell individually in Jupyter Notebook or some other platform that works well with jupyter notebooks such as Google Colab. You can install Jupyter Notebook with the command:
- pip install notebook

And open the IDE environment with:
- jupyter notebook

No parameters should be necessary to run any of the cells.
