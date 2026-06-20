# Titanic Survival Prediction 🚢

This project uses Machine Learning to predict whether a passenger survived the Titanic disaster based on passenger information such as age, gender, passenger class, fare, and family relationships.

---

## 📊 Dataset
The dataset used in this project is the **Titanic dataset** sourced from **Kaggle**.

---

## 🛠 Technologies Used
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-learn
* **Visualization:** Matplotlib

---

## ⚙️ Data Preprocessing & Feature Engineering
The following preprocessing steps were applied to clean and prepare the data:
* **Handling Missing Values:**
  * Filled missing values in the `Age` column using the **median** value.
  * Filled missing values in the `Embarked` column using the **most frequent** value (mode).
  * Removed the `Cabin` column due to a large percentage of missing values.
* **Categorical Encoding:** Converted categorical variables (`Sex` and `Embarked`) into numerical values.

---

## 📋 Model & Features

### Features Used
* `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`

### Machine Learning Model
* **Algorithm:** Random Forest Classifier

---

## 🚀 Results
The model achieved a solid performance on the test data:

| Metric | Score |
| :--- | :--- |
| **Accuracy** | **82.68%** |

---

## 📁 Project Structure
```text
titanic-survival-prediction/
│
├── titanic_survival_prediction.ipynb   # Jupyter Notebook containing the ML workflow
└── README.md                           # Project documentation
