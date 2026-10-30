# Regularization and Stability

*Statistical Methods for Machine Learning — Master in Data Science for Economics*

This project studies, empirically, how regularisation affects the stability of least squares, following the algorithmic stability viewpoint of Bousquet and Elisseeff (2002). OLS and ridge regression are implemented from scratch with NumPy. On the Diabetes dataset and on a synthetic dataset, the code measures the training and test error against the regularisation strength λ, the stability of the algorithm when one training example is removed, and how stability relates to the generalisation gap. An extension studies the effect of the training set size.

## Contents

- **`Regularization_and_Stability_codes.ipynb`**: notebook containing all the code
- **`Regularization_and_Stability_report.pdf`**: the report, which describes the methodology, the experiments and the results in detail
- **`requirements.txt`**: numpy, matplotlib, scikit-learn, jupyter
