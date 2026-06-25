# CS505 – Data Mining: Mountains vs. Beaches Preferences

## 📘 Course Information

- **Course:** CS505 – Data Mining  
- **Term:** Fall 2024  
- **Institution:** Bishop's University  
- **Project Type:** Final Project  
- **Topic:** Preference Analysis using Data Mining Techniques  

---

## 📌 Project Overview

This project analyzes survey data to understand preferences between **mountains** and **beaches** using data preprocessing, feature encoding, exploratory analysis, and data mining techniques implemented in Python.

Key tasks include:
- Data cleaning and preprocessing
- Categorical feature encoding
- Exploratory Data Analysis (EDA)
- Classification and pattern mining
- Interpretation of results using data mining concepts

---

## 📊 Dataset

The dataset consists of survey responses capturing user preferences related to mountains vs. beaches, travel habits, and lifestyle indicators.

Two versions are included:
- `data/mountains_vs_beaches_preferences.csv` — raw survey data
- `data/encoded_dataset.csv` — preprocessed and encoded version ready for analysis

---

## 🧠 Techniques Used

- Data preprocessing and cleaning
- Categorical feature encoding (Label Encoding / One-Hot Encoding)
- SMOTE for class balancing
- StandardScaler + PCA (95% variance retained)
- Exploratory Data Analysis (EDA) — histograms, violin plots, heatmaps, scatter plots
- Classification: Decision Tree, SVM, Neural Network (MLP)
- Hyperparameter tuning: GridSearchCV, RandomizedSearchCV, HalvingGridSearchCV
- Model validation: K-Fold Cross-Validation, Leave-One-Out
- Learning curve visualization

---

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn

---

## 📂 Project Structure

```
cs505-datamining-mountains-vs-beaches/
├── notebooks/
│   └── Final_Project.ipynb     # Main analysis notebook
├── data/
│   ├── mountains_vs_beaches_preferences.csv
│   └── encoded_dataset.csv
├── report/
│   └── Final_Project.pdf
├── .gitignore
└── README.md
```

---

## ▶️ How to Run

1. Open the notebook in Jupyter or Google Colab:
   ```bash
   jupyter notebook notebooks/Final_Project.ipynb
   ```

2. Install required libraries if needed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

---

## 📝 Notes

This project was developed as part of an academic course.  
The code is intended for educational and research purposes only.

## 👤 Author

**Ahmad Issa**  
Machine Learning Engineer | AI & Data Science  
[GitHub](https://github.com/issa89ai) · [LinkedIn](https://linkedin.com/in/ahmadissa)
