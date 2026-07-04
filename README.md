# ❤️ Heart Disease Prediction using Logistic Regression

A Machine Learning project that predicts the likelihood of a person developing heart disease within the next 10 years using the **Framingham Heart Study** dataset and the **Logistic Regression** algorithm.

---

# 📌 Project Overview

This project applies Logistic Regression to classify whether a patient is at risk of coronary heart disease (CHD) within the next 10 years. It includes data preprocessing, exploratory data analysis (EDA), model training, and prediction.

---

# 🎯 Objective

- Predict the 10-year risk of heart disease.
- Perform Exploratory Data Analysis (EDA).
- Handle missing values.
- Train a Logistic Regression classification model.
- Evaluate the model's performance.

---

# 📂 Dataset

**Dataset:** `framingham.csv`

**Target Variable**

- `TenYearCHD`
  - 1 → High risk of heart disease
  - 0 → Low risk of heart disease

The dataset contains demographic, medical history, lifestyle, and clinical measurements.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

---

# 📚 Machine Learning Workflow

1. Import required libraries
2. Load the dataset
3. Perform Exploratory Data Analysis (EDA)
4. Handle missing values using median imputation
5. Separate features and target
6. Split data into training and testing sets
7. Train the Logistic Regression model
8. Predict heart disease risk
9. Evaluate the model

---

# 📁 Project Structure

```text
Heart-Disease-Prediction/
│
├── framingham.csv
├── Heart_Diseases_Prediction.ipynb
├── README.md
```

---

# 🚀 Installation

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git

cd Heart-Disease-Prediction

pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

---

# ▶️ Run the Project

```bash
jupyter notebook
```

Open **Heart_Diseases_Prediction.ipynb** and run all cells.

---

# 📊 Exploratory Data Analysis

The notebook includes:

- Dataset information
- Summary statistics
- Missing value analysis
- Duplicate value check
- Feature distribution
- Data preprocessing

---

# 📈 Model Used

**Logistic Regression**

Since the target variable is binary (0 or 1), Logistic Regression is used to estimate the probability of heart disease occurrence.

---

# 📖 Concepts Covered

- Binary Classification
- Logistic Regression
- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Selection
- Model Evaluation

---

# 🔮 Future Improvements

- Hyperparameter tuning
- Feature engineering
- Cross-validation
- ROC Curve & AUC Score
- Confusion Matrix
- Precision, Recall & F1 Score
- Compare with Decision Tree, Random Forest, and XGBoost

---

# 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

# 📄 License

This project is intended for educational and learning purposes.

---

# 👨‍💻 Author

**Heet Bhatt**

Currently pursuing **AI & ML** and building Machine Learning projects to strengthen practical skills.

⭐ If you found this project useful, consider giving it a star on GitHub.
