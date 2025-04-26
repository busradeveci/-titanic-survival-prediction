# Titanic Survival Prediction 🚢

This project uses the Titanic dataset to predict passenger survival using the **Random Forest** algorithm.

## 💡 Overview
I started with a Titanic dataset where the initial model accuracy was just 39%.
After carefully cleaning the data, handling missing values, and applying simple yet effective preprocessing steps, I was able to significantly improve the prediction accuracy.
My goal was to keep the project clean, educational, and beginner-friendly — no unnecessary complications.

## 🧠 What I Did
- Removed unnecessary columns like `Name`, `Ticket`, `Cabin`, etc.
- Handled missing values using `SimpleImputer` and mode/mean filling.
- Converted categorical features like `Sex` and `Embarked` into numbers.
- Split the data into training and testing sets.
- Trained a Random Forest classifier.
- Evaluated accuracy using `accuracy_score`.

## 📊 Model
- **Algorithm**: RandomForestClassifier  
- **Accuracy**: ~**80%**

## 📁 Files
- `titanic.csv` – The dataset  
- `notebook.ipynb` – Main notebook  
- `README.md` – This file  

## 🔍 Usage
To run this project:

```bash
pip install pandas scikit-learn
```

Then open the notebook and run it step by step.

## ✨ Author
Created by [@busradeveci](https://www.kaggle.com/busradeveci)  
Feel free to use, learn, and share ✨
