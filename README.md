# Customer Churn Prediction

## Project Overview

This project focuses on predicting **customer churn in the telecommunications industry**.
Customer churn refers to when customers stop doing business with a company. Identifying potential churners in advance allows businesses to design better **customer retention strategies**.

## Business Objectives

1. **Identify churners**: Predict which customers are likely to leave.
2. **Understand churn drivers**: Analyze key factors contributing to churn.
3. **Improve retention**: Use insights to guide business decisions.

## Data Science Objectives

* Build supervised **classification models** (Logistic Regression, Random Forest, Gradient Boosting).
* Evaluate models using **accuracy, precision, recall, F1-score, and ROC-AUC**.
* Apply **feature importance** and **SHAP explainability** to interpret results.

---

## Dataset

The dataset is split into two files:

* `churn-bigml-80.csv` → Training data (80%)
* `churn-bigml-20.csv` → Test data (20%)

**Key features include:**

* Demographics (e.g., state, account length).
* Services (e.g., international plan, voicemail plan).
* Usage (day/evening/night call minutes & charges).
* Customer service interactions.
* **Target**: `Churn` (Yes/No).

---

## Installation & Requirements

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction
pip install -r requirements.txt
```

### Main Python Libraries

* `pandas`, `numpy` → Data handling
* `matplotlib`, `seaborn` → Visualization
* `scikit-learn` → Machine learning models
* `shap` → Explainability

---

## Usage

Run the Jupyter Notebook:

```bash
jupyter notebook Customer_churn.ipynb
```

Steps inside the notebook:

1. Load and merge datasets.
2. Perform **EDA (Exploratory Data Analysis)**.
3. Train and evaluate classification models.
4. Visualize results and interpret feature importance.

---

## Results

* **Best performing model**: Gradient Boosting (highest ROC-AUC).
* **Top churn drivers**:

  * International plan subscription.
  * Number of customer service calls.
  * Total day minutes & charges.

---

## Future Work

* Hyperparameter tuning with GridSearchCV.
* Try deep learning models (e.g., Neural Networks).
* Deploy model via Flask/FastAPI for real-time predictions.

---

## Author

Developed by **\[Anouar Jebri]**
For questions or collaborations, feel free to reach out!