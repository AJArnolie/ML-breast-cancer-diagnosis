# ML-breast-cancer-diagnosis

## Project Overview:
This repo contains a Machine Learning research project (completed at MIT for an MIT STEM research symposium) exploring the possibility of using Machine Learning to predict breast cancer diagnoses (malignant or benign) based on a number of quantitative observations of a mass of cells in a breast cancer lesion including area, compactness, and cell concavity. Using a number of ML and data analysis modules (listed below) in Python, we first cleaned a dataset with approximately 600 observation entries and used a correlation heat map to determine which features in the data had the highest correlation values in relation to the final diagnosis. We then highlighted additional interesting correlations between other features. Finally, using the previously selected to train our predictors, we trained predictors on a sample of the data using Machine Learning methods such as Linear Regression, Logistic Regression, SVM, Decision Tree, KNN, etc. We then selected the most effective methods and documented these methods in the provided file.

## Setup and Installation
### Installing Required Packages
To install the required packages for this project, use the requirement.txt file included in the directory with `python3 -m pip install -r requirements.txt`. 

```python
pandas==1.0.5
numpy==1.17.4
matplotlib==3.3.1
sklearn==0.0
scipy==1.5.2
notebook==6.1.3
jupyterlab==2.2.5
```

### Running the Notebook
After the required packages have been installed, to run the notebook, type the following command into the command line to open Jupyter Notebook:
```
jupyter notebook
```
Then, simply find the project folder, open the .ipynb file, and run.
