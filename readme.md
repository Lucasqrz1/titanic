# Titanic Survival Prediction – Machine Learning

## Project Overview

This project is based on the **Titanic: Machine Learning from Disaster** Kaggle competition.  
The goal is to build a machine learning model that predicts whether a passenger survived the Titanic shipwreck using demographic and socioeconomic features.

The project follows a standard data science workflow: data exploration, preprocessing, feature engineering, model training, evaluation, and submission generation.

---

## Dataset

**Source:** Kaggle – Titanic: Machine Learning from Disaster

**Files:**
- `train.csv` – training dataset with labels
- `test.csv` – test dataset without labels
- `gender_submission.csv` – baseline submission example

**Target Variable:**
- `Survived`
  - `0` = Did not survive
  - `1` = Survived

---

## Features (Main)

- `Pclass` – Passenger class (1st, 2nd, 3rd)
- `Sex` – Gender
- `Age` – Age
- `SibSp` – Siblings / spouses aboard
- `Parch` – Parents / children aboard
- `Fare` – Ticket fare
- `Embarked` – Port of embarkation

---

## Methodology

### Exploratory Data Analysis
- Survival distribution
- Survival vs. gender, class, age, fare
- Missing value analysis

### Data Preprocessing
- Handling missing values (`Age`, `Embarked`, `Fare`)
- Encoding categorical variables
- Feature selection

### Feature Engineering
- Family-based features
- Binary and numerical transformations

### Modeling
Models evaluated:
- Logistic Regression
- Decision Tree
- Random Forest

### Evaluation
- Accuracy
- Cross-validation
- Model comparison

### Submission
- Predictions generated on test data
- Submission formatted for Kaggle

---

## Results

- Best model: **Random Forest**
- Validation accuracy: ~XX%
- Kaggle public score: ~XX%

---

## Project Structure

├── data/
│ ├── train.csv
│ ├── test.csv
│ └── gender_submission.csv
├── notebooks/
│ └── titanic.ipynb
├── src/
│ ├── preprocessing.py
│ ├── feature_engineering.py
│ └── model.py
├── README.md
└── requirements.txt


---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the notebook or scripts

4. Generate the Kaggle submission file

## Key Learnings

- End-to-end machine learning pipeline

- Data cleaning and preprocessing

- Feature engineering

- Model evaluation and comparison