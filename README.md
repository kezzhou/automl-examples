# AutoML Examples
HHA 507 // Week 11 // Assignment 9


## Description:

In this repository we create two example experiments using AutoML package mljar-supervised: one binary classification and one regression - the outputs of which are stored in their respective folders. The dataset of choice is a modified version of a SPARCS dataset, which is provided in the resources section below.

Binary Classification:
For our binary classification experiment, we chose 'Ethnicity' as our binary variable of choice. Xgboost is selected as the best of the models based on log-loss metric.

Regression:
For our regression experiment, we chose 'Total Costs' as our continuous variable of choice. Ensemble is selected as the best of the models based on the rmse metric.


## Components:

1. autoML.ipynb (Jupyter Notebook)

2. Classification - Binary (Folder)

3. Regression (Folder)


## Resources:

[Dataset - Modified SPARCS](https://raw.githubusercontent.com/hantswilliams/HHA-507-2022/main/autoML/datasets/data_sparcs.csv)

[Source Code](https://colab.research.google.com/github/hantswilliams/HHA-507-2022/blob/main/autoML/autoML.ipynb?authuser=1#scrollTo=W7Vofhvog3OD)


## Requirements:

- Jupyter/Google Colab/Equivalent
- Visual Studio Code/Equivalent
- SVG VS Code Extension/Equivalent


## Notes:

It's important to note that by default, Google Colab may not save outputs when saved locally as a notebook. This can be modified by navigating to Edit > Notebook Settings > Uncheck "Omit code cell output when saving this notebook" within Google Colab.

The SVG Extension in VS Code is necessary to view a few components of the models' outputs.

We've modified the ipynb file to contain two zipping codes: one for the classification experiment and one for the regression.
