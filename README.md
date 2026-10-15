# Customer Churn Prediction using Logistic Regression

A machine learning project that predicts whether a customer is likely to leave (churn) using **Logistic Regression**. The full workflow, from loading and cleaning the data to training and evaluating the model, lives in a single Jupyter Notebook.

> Identifying customers at risk of churning lets a business act early, for example with targeted retention offers, instead of reacting after the customer has gone.

## Project Overview

- **Goal:** Build a binary classifier that predicts customer churn (churned vs. retained).
- **Model:** Logistic Regression.
- **Format:** Jupyter Notebook (`.ipynb`), runnable locally or in Google Colab.

## Repository Structure

```
Customer-Churn-Prediction-using-Logistic-Regression/
├── Data/                                                  # Dataset used in the notebook
└── Customer_Churn_Prediction_Using_Logistic_Regression.ipynb   # Full analysis and model
```

## Workflow

1. **Data loading:** Import the dataset from the `Data/` folder.
2. **Data cleaning:** Handle missing values, fix data types and remove inconsistencies.
3. **Exploratory data analysis (EDA):** Examine the churn distribution and how features relate to churn.
4. **Preprocessing:** Encode categorical variables and scale numeric features where needed.
5. **Train/test split:** Hold out a portion of the data to evaluate the model on unseen customers.
6. **Model training:** Fit a Logistic Regression classifier.
7. **Evaluation:** Assess performance with accuracy, precision, recall, F1-score and a confusion matrix.

<!-- Edit the steps above to match exactly what your notebook does. -->

## Dataset

The dataset is stored in the [`Data/`](Data) folder.

- **Source:** _[add the dataset source, e.g. Kaggle link]_
- **Rows / columns:** _[add size]_
- **Target variable:** _[add the churn column name]_
- **Key features:** _[e.g. tenure, contract type, monthly charges, services subscribed]_

## Results

| Metric | Score |
| --- | --- |
| Accuracy | _[add]_ |
| Precision | _[add]_ |
| Recall | _[add]_ |
| F1-score | _[add]_ |

**Key findings:** _[add 2 to 3 short insights, e.g. which features most strongly drive churn]_

## Tech Stack

- Python 3
- pandas, NumPy
- Matplotlib / Seaborn
- scikit-learn
- Jupyter Notebook

## Getting Started

### Prerequisites

- Python 3.8 or newer
- `pip`

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/KinneryAnyanga/Customer-Churn-Prediction-using-Logistic-Regression.git
cd Customer-Churn-Prediction-using-Logistic-Regression

# 2. (Optional) create and activate a virtual environment
python -m venv venv
source venv/bin/activate        # macOS/Linux
venv\Scripts\activate           # Windows

# 3. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run the notebook

```bash
jupyter notebook Customer_Churn_Prediction_Using_Logistic_Regression.ipynb
```

You can also upload the notebook and the `Data/` folder to [Google Colab](https://colab.research.google.com/) and run it there.

## Possible Improvements

- Compare Logistic Regression against Random Forest, XGBoost and other classifiers.
- Handle class imbalance (e.g. SMOTE or class weights).
- Tune hyperparameters with cross-validation and grid search.
- Add feature importance or coefficient analysis to explain churn drivers.
- Package the model into a small app (e.g. Streamlit) for live predictions.

## Author

**Kinnery Anyanga**
GitHub: [@KinneryAnyanga](https://github.com/KinneryAnyanga)
Organisation: KeDataLab
