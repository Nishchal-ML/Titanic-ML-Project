# 🛳️ Titanic - Machine Learning from Disaster

This project is built around Kaggle’s famous Titanic competition. The objective is to predict which passengers survived the Titanic shipwreck based on features like age, gender, ticket class, etc.

---

## 🎯 Objective

Build a machine learning model that can accurately predict passenger survival using classification techniques, while applying sound data science practices like EDA, feature engineering, model evaluation, and cross-validation.

---

## 📊 Key Highlights

- ✅ Performed thorough exploratory data analysis (EDA) using seaborn and matplotlib
- ✅ Handled missing values in `Age`, `Embarked`, and `Cabin` strategically
- ✅ Engineered meaningful features:
  - `Title` extracted from names
  - `FamilySize` and `IsAlone` from SibSp and Parch
  - `Fare_to_Class` as a ratio feature
- ✅ Used `Pipeline` and `ColumnTransformer` for preprocessing
- ✅ Trained a `RandomForestClassifier` with `GridSearchCV` for hyperparameter tuning
- ✅ Evaluated using:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix (with TP, TN, FP, FN explanation)
  - Cross-validation (3-fold)
- ✅ Achieved **0.78947** on Kaggle public leaderboard (Top ~9%)

---

## 📁 Dataset

- [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic)
- Files used:
  - `train.csv`
  - `test.csv`

---

## 🛠️ Tech Stack

- **Language**: Python 3  
- **Libraries**:
  - pandas
  - numpy
  - matplotlib & seaborn (EDA & visualizations)
  - scikit-learn (modeling and evaluation)

---

## 📈 Model Performance

| Metric                    | Score     |
|---------------------------|-----------|
| Kaggle Leaderboard Score  | **0.78947** |
| Validation Accuracy       | ~83%      |
| Cross-Validation (CV=3)   | ~81%      |

---

## 📂 Project Structure

📁 Titanic-Machine-Learning  
├── Titanic_Project.ipynb
├── submission.csv  
└── README.md  


---

## ✅ Next Steps

- Try ensembling with Voting Classifier or XGBoost
- Perform stratified K-fold cross-validation
- Test feature importance using SHAP values or permutation
- Optional: deploy using Streamlit or Gradio

---

## 👤 Author

**Nishchal Pandey**  
*Aspiring Data Scientist & BI Analyst*

🔗 [LinkedIn](https://www.linkedin.com/in/nishchal-pandey)

---

## 🏁 Conclusion

This project demonstrates a complete ML pipeline — from raw data to cleaned features and tuned models — evaluated through multiple metrics and submitted to Kaggle for real-world benchmarking.

Feel free to fork, explore, and learn!
