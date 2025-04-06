# 🚢 Titanic Survival Prediction

This is a beginner-level data science project that aims to predict the survival of passengers on the Titanic using machine learning algorithms. It is based on the famous Titanic dataset from Kaggle's [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic) competition.

## 📊 Problem Statement

The goal is to build a model that predicts whether a passenger survived the Titanic shipwreck or not, based on features like age, sex, class, fare, and others.

## 🧠 Tools & Technologies

- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn for data visualization
- Scikit-learn for machine learning
- Jupyter Notebook

## 🛠️ Project Workflow

1. **Data Loading & Exploration**
   - Load and understand the dataset
   - Handle missing values
   - Explore distributions and relationships

2. **Feature Engineering**
   - Encode categorical features
   - Create new features (e.g., `Title`, `FamilySize`, etc.)
   - Scale/transform data if necessary

3. **Modeling**
   - Train different classification models:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - K-Nearest Neighbors
   - Evaluate performance with metrics like accuracy and confusion matrix

4. **Prediction**
   - Apply the trained model to the test dataset
   - Generate submission file for Kaggle

## 📁 Dataset

The dataset includes the following files:

- `train.csv` — Training data
- `test.csv` — Test data

Key columns:
- `Pclass`: Passenger class (1st, 2nd, 3rd)
- `Sex`: Gender
- `Age`: Age in years
- `SibSp`: # of siblings / spouses aboard
- `Parch`: # of parents / children aboard
- `Fare`: Passenger fare
- `Embarked`: Port of Embarkation
- `Survived`: Target variable (0 = No, 1 = Yes)

## 📈 Results

The best-performing model achieved an accuracy of approximately **75%**.  
Further improvements are possible with hyperparameter tuning and advanced models.


## ✅ What I Learned

- Data cleaning and preprocessing techniques
- Handling missing values and encoding categories
- Feature selection and model comparison
- Evaluating model performance with multiple metrics

