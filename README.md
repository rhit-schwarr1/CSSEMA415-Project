# CSSEMA415 Project

## Project Overview

This project focuses on machine learning techniques for drug discovery and virtual screening. The notebooks and scripts explore multiple classification and predictive modeling approaches, including Logistic Regression, K-Nearest Neighbors (KNN), Random Forests, Gradient Boosting, Principal Component Analysis (PCA), Support Vector Machines (SVM), and feature engineering techniques.

The project compares the performance of different machine learning models using chemical and drug discovery datasets. The analysis includes preprocessing, model training, evaluation, visualization, and performance comparison.

---

# Project Structure

```text
CSSEMA415-Project-main/
│
├── data/
│   ├── chembl_36_cleaned_balanced.csv
│   ├── drug_discovery_virtual_screening.csv
│   ├── drug_discovery_virtual_screening_cleaned.csv
│   └── r2gradboosting.csv
│
├── src/
│   ├── main.py
│   ├── Baseline.ipynb
│   ├── Chembl36Analysis.ipynb
│   ├── Demo.ipynb
│   ├── GradientBoostedTrees.ipynb
│   ├── GradientBoostingTrees2.ipynb
│   ├── KNN.ipynb
│   ├── LogisticRegression.ipynb
│   ├── ModelComparison.ipynb
│   ├── PCAandSVM.ipynb
│   ├── PolyFeatures.ipynb
│   ├── RandomForest.ipynb
│   ├── RidgeVsLasso&ThresholdTuning.ipynb
│   ├── Statistics.ipynb
│   └── demo.csv
│
├── requirements.txt
├── pyproject.toml
└── README.md
```

---

# Dependencies and Installation

## Python Version

This project was developed using Python 3.10+.

## Required Packages

Install all required dependencies using:

```bash
pip install -r requirements.txt
```

The main libraries used in this project include:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

If additional packages are missing, install them with:

```bash
pip install <package-name>
```

---

# Dataset Information

The datasets used in this project are stored in the `data/` folder.

## Dataset Files

| File Name | Description |
|---|---|
| `chembl_36_cleaned_balanced.csv` | Balanced ChEMBL dataset used for machine learning classification tasks |
| `drug_discovery_virtual_screening.csv` | Raw drug discovery virtual screening dataset |
| `drug_discovery_virtual_screening_cleaned.csv` | Cleaned version of the virtual screening dataset |
| `r2gradboosting.csv` | Dataset/results related to gradient boosting evaluation |

## Data Location

All dataset files must remain inside the `data/` folder for the notebooks and scripts to run correctly.

Example:

```text
CSSEMA415-Project-main/data/
```

If the datasets are moved or renamed, file paths inside the notebooks and scripts may need to be updated.

---

# Running the Project

## Option 1: Run the Main Python Script

Navigate to the `src/` folder:

```bash
cd src
```

Run the main script:

```bash
python main.py
```

---

## Option 2: Run Jupyter Notebooks

Start Jupyter Notebook from the project directory:

```bash
jupyter notebook
```

Open any notebook from the `src/` folder to explore the analysis and machine learning models.

Recommended notebooks to review:

- `ModelComparison.ipynb`
- `RandomForest.ipynb`
- `GradientBoostedTrees.ipynb`
- `PCAandSVM.ipynb`
- `LogisticRegression.ipynb`

---

# Machine Learning Techniques Used

The project evaluates and compares several machine learning methods, including:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest
- Gradient Boosting
- Ridge and Lasso Regression
- Principal Component Analysis (PCA)
- Support Vector Machines (SVM)
- Polynomial Feature Engineering

Performance metrics and visualizations are used to compare the effectiveness of each model.

---

# Outputs and Results

The notebooks generate:

- Accuracy metrics
- Model comparison results
- Graphs and visualizations
- Feature analysis
- Classification performance evaluations

Some outputs may also be saved as CSV files inside the project folders.

---

# Notes

- Ensure all dataset files are present before running the notebooks or scripts.
- Some notebooks may require running cells sequentially.
- Large datasets may increase runtime depending on system performance.

---

# Authors

CSSEMA415 Project Team
