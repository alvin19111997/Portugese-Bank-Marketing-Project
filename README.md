# Portuguese Bank Marketing

## Problem
Predict whether a client will subscribe to a term deposit from the Portuguese bank marketing campaign data.

## Data
The project uses Portuguese Bank Marketing data. The repository currently contains the analysis notebook; the dataset is not included in the repository root.

## Approach
- Preprocessed the data and handled class imbalance.
- Compared candidate models and used XGBoost for the final model.
- Tuned the model with GridSearchCV.

## Result
The model reached **84.53% accuracy**.

## How to Run
1. Clone this repository.
2. Install Python, Jupyter, pandas, NumPy, scikit-learn, and XGBoost.
3. Open and run `PortugeseBankMarketing.ipynb`.
4. Place the expected dataset in the location referenced by the notebook; data files are not included here.

## Tech Stack
Python, pandas, NumPy, scikit-learn, XGBoost, GridSearchCV, Jupyter Notebook