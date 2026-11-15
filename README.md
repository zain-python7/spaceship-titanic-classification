# Spaceship Titanic – Passenger Transportation Prediction

## Project Overview

This project focuses on predicting whether passengers aboard the Spaceship Titanic were transported to an alternate dimension following a mysterious spacetime anomaly.

The project uses machine learning, exploratory data analysis, feature engineering, and hyperparameter tuning to build a classification model.

## Dataset

The dataset comes from the Kaggle Spaceship Titanic competition.

- `train.csv` Training dataset containing passenger information and the target variable.
- `test.csv` Test dataset used to generate predictions.
- Target variable `Transported`

## Project Structure

```text
spaceship-titanic-classification
├── data
│   ├── train.csv
│   └── test.csv
├── notebooks
│   └── spaceship_titanic_analysis.ipynb
├── submissions
│   └── spaceship_titanic_final.csv
├── README.md
├── requirements.txt
└── 
```

## Techniques Used

- Exploratory Data Analysis (EDA)
- Missing Value Handling
- Feature Engineering
- Categorical and Numerical Data Preprocessing
- Stratified K-Fold Cross-Validation
- GridSearchCV Hyperparameter Tuning
- Classification Model Evaluation

## Feature Engineering

Several additional features were created, including

- GroupSize and IsAlone
- Deck, CabinNumber, and Side
- FamilySize
- TotalSpend
- SpendMissingCount
- SpendCategoriesUsed
- NoSpend
- AgeGroup and IsChild

## Machine Learning Model

The final model is a HistGradientBoostingClassifier integrated into a preprocessing pipeline.

Hyperparameter tuning was performed using GridSearchCV.

Best cross-validation accuracy 81.53%

## Kaggle Performance

- Public Leaderboard Score 0.81038
- Kaggle Rank 198 (at the time of submission)

## Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## How to Run

1. Clone this repository.
2. Install the required libraries.
3. Open the notebook in Jupyter Notebook or VS Code.
4. Run the notebook cells.

## Competition

[Kaggle – Spaceship Titanic](httpswww.kaggle.comcompetitionsspaceship-titanic)

---

Project Spaceship Titanic Classification  
Task Binary Classification  
Target Transported
