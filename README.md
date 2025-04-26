# Titanic Survival Prediction 🚢

This project uses the Titanic dataset to predict passenger survival using the **Random Forest** algorithm.

## 💡 Overview
At first, the model had only **39% accuracy**, but after careful data cleaning and preprocessing, we improved the prediction accuracy significantly. The goal was to keep it **simple, educational, and effective** — without unnecessary complexity.

## 🧠 What We Did
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
