# Titanic Survival Prediction

## Overview  
This project applies machine learning techniques to predict whether a passenger survived the Titanic disaster. The predictions are based on various features such as ticket class, gender, age, fare, and embarkation point.

---

## Dataset  
The dataset used is the Titanic dataset provided by the `seaborn` library.

### Features:
- **pclass** – Ticket class (1st, 2nd, 3rd)  
- **sex** – Gender of the passenger  
- **age** – Age of the passenger  
- **sibsp** – Number of siblings/spouses aboard  
- **parch** – Number of parents/children aboard  
- **fare** – Ticket fare  
- **embarked** – Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)  

### Target:
- **survived** – 1 if the passenger survived, 0 otherwise  

---

## Data Preprocessing  
- Handled missing values using `SimpleImputer`  
- Encoded categorical features (`sex` and `embarked`) using `LabelEncoder`  
- Standardized numerical features using `StandardScaler`  
- Split the dataset into training (80%) and testing (20%) sets  

---

## Models Used  
The following machine learning models were implemented:  
- **Logistic Regression**  
- **Naive Bayes (GaussianNB)**  
- **Random Forest Classifier**  

---

## Results  
The performance of each model was evaluated based on accuracy:

- **Logistic Regression** – 79.89%  
- **Naive Bayes** – 77.65%  
- **Random Forest** – 81.56%  

The **Random Forest Classifier** achieved the highest accuracy of **81.56%**.

---

## Visualization  
Confusion matrices for each model were plotted using **Seaborn's heatmap** to visualize the classification performance.

---
