# Intelligent Systems for Bioinformatics Curricular Unit - Group 3
# Drug Synergy Prediction

This repository contains the work developed in the scope of Intelligent Systems for Bioinformatics Curricular Unit by group 3 with contribution of:
- [Christian Neitzel](https://github.com/ChristianNeitzel)
- [Diana Silva](https://github.com/dianasilvaaaa)
- [Ian Alves](https://github.com/ianalvess)
- [Samuel Baptista](https://github.com/tsamuelabaptista)

This repository is organized into 4 sections as follows:

## Section 1 - Data exploration and preprocessing

Section 1 includes loading the original data, an exploratory analysis and preprocessing of the data to use on the following sections.

## Section 2 - Unsupervised Learning

Section 2 includes dimensionality reduction and clustering unsupervised learning techniques such as PCA, t-SNE, k-means and hierarquical clustering to try to uncover patterns in the data.  

## Section 3 - Supervised Learning: Machine Learning

Section 3 includes a machine learning pipeline to predict synergy scores with the following pipeline:

- Feature selection with scikit-learn SelectFromModel to reduce the number of features of our dataset.

- Training several models with scikit-learn, including lasso regression, ridge regression, random forest, support vector machine (SVM), k-nearest neighbors (KNN), voting (with the previous regressors), bagging, boosting, and stacking.

- Model validation with scikit-learn cross-validation.

- Hyperparameter tuning of the best model (random forest) with scikit-learn RandomizedSearchCV.

- Interpretation of the best model with scikit-learn feature importance and permutation importance. 

## Section 4 - Supervised Learning: Deep Learning

Section 4 includes a deep learning pipeline to predict synergy scores with the following pipeline:

- Data preprocessing of Drug1 and Drug2 smiles, including character encoding and sequences padding.

- Build and train a multi input reccurent neural network (RNN) and convolutional neural network (CNN).
