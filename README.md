# Tennis Outcome Prediction
This repository contains the code and data for my M.Sc. thesis titled "Predicting Tennis Match Outcome: A Machine Learning Approach Using the SRP-CRISP-DM Framework".

# Requirements

1. `Python 3.10`.
2. The requirements in `requirements.txt`.

# Getting started

- Install the requirements listed in `requirements.txt`. You should be able to do this using `pip install -r requirements.txt`.

# Overview of the repository

The repository contains a series of Jupyter Notebook files that document the entire process of the study, from dataset creation to exploratory data analysis. Each `.ipynb` file is prefixed with a number indicating its order in the workflow:

- `_0_dataset_creation.ipynb`: This notebook outlines the initial steps taken to create the dataset used for the model, including data sourcing and preliminary processing.
- `_1_dataset_analysis.ipynb`: This file provides an in-depth analysis of the dataset, offering insights into its composition and potential challenges for modeling.
- `_2_target_transformation.ipynb`: Here, the target variable is transformed to suit the requirements of the predictive modeling process.
- `_3_betting_odds.ipynb`: This notebook examines the betting odds information, which is crucial for feature generation and predictive analysis.
- `_4_missing_data_handling.ipynb`: This file addresses how missing data within the dataset is identified and handled to ensure model integrity.
- `_5_feature_extraction.ipynb`: In this notebook, various feature extraction techniques are applied to the dataset to prepare it for the modeling phase.
- `_6_data_preparation.ipynb`: This file details the steps taken to prepare the data for training, including normalization, scaling, and splitting into training and testing sets.
- `_6_exploratory_data_analysis.ipynb`: The final notebook in the sequence provides an exploratory analysis of the data, visualizing patterns and relationships that inform the subsequent modeling approach.

These notebooks contain executable code, visualizations, and narrative explanations that guide you through the methodology of the study.

