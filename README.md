# VEGFR2 (Vascular Endothelial Growth Factor Receptor 2)

This repository contains the code and resources used for developing a Quantitative Structure-Activity Relationship (QSAR) model to predict the biological activity of compounds targeting VEGFR2 (Vascular Endothelial Growth Factor Receptor 2). The project is based on the VEGFR2_QSAR_Modeling.ipynb Jupyter notebook.

The goal is to build a robust predictive model to assist in drug discovery related to VEGFR2 inhibition. All necessary steps, from data loading and preprocessing to model training and evaluation, are included.

## Jupyter Notebook
The primary file for this project is the VEGFR2_QSAR_Modeling.ipynb Jupyter notebook. This notebook guides you through the following key stages of QSAR modeling:

1.	Data Loading & Exploration: The notebook loads the dataset, performs exploratory data analysis (EDA), and visualizes the distribution of activity values and molecular features.
2.	Data Preprocessing: It includes steps such as:
o	Cleaning the dataset (removing missing or invalid entries).
o	Feature extraction using RDKit to convert SMILES representations into molecular descriptors.
o	Normalizing and splitting the data into training and testing sets.
3.	Model Training: Various machine learning algorithms are trained to predict VEGFR2 activity.
4.	Model Evaluation: The notebook evaluates the performance of the trained model using metrics.

## Requirements
To run the code and recreate the analysis, you will need the following Python libraries:

•	pandas: For data manipulation and cleaning
•	numpy: For numerical operations
•	scikit-learn: For machine learning algorithms and evaluation metrics
•	xgboost: For boosting model training
•	rdkit: For cheminformatics and molecular descriptor extraction
•	matplotlib & seaborn: For data visualization
