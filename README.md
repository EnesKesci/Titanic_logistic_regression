# 🚢 Titanic - Survival Prediction (Logistic Regression)

In this project, I tried to predict whether the passengers in the Titanic accident would survive by looking at their characteristics. I used **Logistic Regression** as a model. I increased the success of the model with data preprocessing, outlier analysis and feature engineering steps.

---

## 📊 Dataset

- **Source:** Kaggle – Titanic: Machine Learning from Disaster
- **Data size:** 891 passengers
- **Target variable:** `Survived` (1: survived, 0: died)

---

## 🛠️ Steps Applied

### 1. Data Cleaning

- Filled missing values ​​(`Age`, `Embarked`)
- Removed meaningless columns for the model such as `Cabin`, `Name`, `Ticket`, `PassengerId`

### 2. Categorical Transformation

- Converted `Sex` and `Embarked` columns to numeric form with `get_dummies()`

### 3. Feature Engineering

- Combined `SibSp` and `Parch` columns **`FamilySize`** column created
- This represents how many family members are with the passenger

---

## 🤖 Model

- Model used: `LogisticRegression` (scikit-learn)
- Training/Testing ratio: 80/20
- Model metrics:
- **Accuracy**
- **Confusion Matrix**
- **Precision / Recall / F1-score**

---

## 📈 Results
> 🔹 FamilySize and log transformations contributed significantly to the model 
> 🔹 Basic level classification was successfully implemented with Logistic Regression
> 🔹 The success rate of the model was measured as 0.80.

---

## 📚 Technologies Used

- Python 3.x
- pandas
- seaborn & matplotlib
- scikit-learn

---

## ✍️ What I Learned

- Classification structure with Logistic Regression
- Data preprocessing (missing value filling, column transformation)
- Outlier analysis
- Improving the model with feature engineering
