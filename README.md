# Deep Learning Lab 1 - DNN/MLP for Regression & Classification  
**Université Abdelmalek Essaadi - Faculté des Sciences et Techniques de Tanger**  
**Département Génie Informatique - Master MBD**  
**Deep Learning**  
**Pr. ELAACKAK LOTFI**

## Objective
The main purpose of this lab is to get familiar with the PyTorch library to design, train, and evaluate Deep Neural Network / Multi-Layer Perceptron (DNN/MLP) architectures for both regression and multi-class classification tasks.

## Repository Contents
- `part1-regression.ipynb` – Complete implementation of the regression task  
  Dataset: NYSE Stock Prices (https://www.kaggle.com/datasets/dgawlik/nyse)  
  Tasks performed:
  - Exploratory Data Analysis (EDA) & visualization
  - Data preprocessing & scaling
  - DNN architecture in PyTorch (GPU-enabled)
  - Hyperparameter search (learning rate, optimizers, architecture)
  - Training with loss/epoch curves
  - Application and comparison of several regularization techniques (Dropout, L2, etc.)

- `part2-classification_analysis.ipynb` – Complete implementation of the multi-class classification task  
  Dataset: Machine Predictive Maintenance Classification (https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)  
  Tasks performed:
  - Data cleaning, standardization & normalization
  - EDA & class imbalance analysis
  - Augmentation techniques to balance classes
  - Multiple DNN models trained and compared
  - Evaluation with accuracy, F1-score, recall, sensitivity
  - Detailed classification report
  - Best model saved as `best_model.pth`

- `eda_plots.png` – Key visualizations generated from the regression notebook

## Requirements
```bash
pip install torch pandas numpy matplotlib seaborn scikit-learn
```

## How to Run
1. Open the notebooks in Google Colab, Kaggle, or Jupyter Lab (GPU runtime recommended).
2. Enable internet access (for loading Kaggle datasets directly).
3. Execute cells sequentially – both notebooks automatically detect and use CUDA if available.

## Tools Used
- Python / PyTorch
- Google Colab / Kaggle Notebooks (GPU)
- GitHub for version control

All requirements of Lab 1 have been fully implemented and documented in the respective notebooks.

**Submitted by:** [Your Full Name]  
**Date:** November 28, 2025
