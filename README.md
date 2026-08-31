# Code for paper: Interpretable multi-element fingerprinting for geographic origin prediction of timber and soybean commodities

## Overview

This repository contains all code developed and used for the analyses conducted as part of my paper, *Interpretable multi-element fingerprinting for geographic origin prediction of timber and soybean commodities*.

The repository consists of two main folders:

* **Pcode**: Python code used for all analyses except data imputation.
* **Rcode**: R scripts used for the data imputation procedures.

---

## Folder Structure

The **Pcode** folder contains four main subfolders:

* **data_preparation**
* **machine_learning**
* **feature_importance**

Each of these folders follows the same architecture:

* A **functions** folder containing all functions developed for the corresponding analyses.
* A **scripts** folder containing the execution scripts used to run these functions.

Each script includes a detailed description at the top explaining its purpose, and the script names reflect their respective functionalities.

---

## Description of Main Analysis Folders

### `data_preparation`

Contains scripts for data cleaning, filtering, and imputation.

### `machine_learning`

Contains the pipelines used for hyperparameter tuning and spatial cross-validation for model performance evaluation.

### `feature_importance`

Contains all feature importance and model interpretability analyses, including permutation importance, SHAP, ALE, and related methods.

---

## Data Confidentiality

The multi-element datasets used in this thesis are confidential and therefore cannot be made publicly available through this repository.

As a result, this repository contains only the code required to reproduce the analyses and workflows described in the thesis.
