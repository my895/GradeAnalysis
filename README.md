# 🎓 Student Grade Analysis 📊

![Banner](https://img.shields.io/badge/Project-Type%3A%20ML%2FData%20Analysis-blueviolet?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Python](https://img.shields.io/badge/Made%20With-Python%203.x-yellow?style=flat-square)

> "Grades don’t define intelligence, but they can reveal patterns."
---
## 🚀 Features

- 🔍 **Data Cleaning & Preprocessing** – Handle missing values and normalize student records.
- 📈 **Descriptive Statistics** – Understand performance through smart metrics.
- 🤖 **Predictive Modeling** – (Optional) Machine learning models to forecast grades.
- 🧠 **Correlation & Causation** – Discover what really impacts student performance.
- 📊 **Visualizations** – Charts and plots to make sense of it all.

---

## 📊 Dataset Information

- **Source**: Portuguese secondary school dataset
- **Total Records**: 395 students
- **Features**: 31 columns including:
  - **Demographic**: Age, Sex, Address (Urban/Rural), Family Size, Parental Cohabitation
  - **Academic**: Previous Grades (G1, G2), Study Time, Number of Past Class Failures, Absences
  - **Parental Info**: Mother’s & Father’s Education Level
  - **Social**: Guardian, Internet Access, Extracurricular Activities, Romantic Relationship

---

## 📁 Project Structure

```
├── data/
│   └── StudentGrades.csv
├── notebooks/
│   └── eda_and_modeling.ipynb
├── models/
│   └── best_model.pkl
├── visuals/
│   └── *.png (plots and graphs)
├── README.md
├── LICENSE
└── requirements.txt
```

---

## 🧹 Data Cleaning

- ✅ No missing values
- ✅ Label Encoding for categorical variables
- ✅ Basic outlier detection
- ✅ Feature engineering based on correlations

---

## 📈 Exploratory Data Analysis (EDA)

### Key Insights

- **Gender**: 52.7% Female, 47.3% Male
- **Age**: Majority between 15–19 years
- **Urban Background**: 77.72% of students
- **Family Size**: 71.14% have families >3 members
- **Parental Cohabitation**: 89.62% live with both parents

### Visuals

- Boxplots: Age vs Final Grades
- KDE Plots: Urban vs Rural Grade Distribution
- Countplots: Categorical feature distributions
- Heatmap: Correlation matrix

---

## 🔍 Correlation Highlights

- **Strong correlation**: G1 and G2 with G3
- **Moderate correlation**: Parental education levels with G3

---

## 🤖 Machine Learning Models

### Models Used

- Linear Regression ✅
- ElasticNet Regression
- Random Forest Regressor
- Extra Trees Regressor
- Support Vector Regressor (SVR)
- Gradient Boosting Regressor

### Evaluation Metrics

| Model                  | MAE   | RMSE  |
|------------------------|-------|-------|
| **Linear Regression**  | 3.49  | 4.43  |
| ElasticNet Regression  | 3.61  | 4.57  |
| Random Forest          | 3.60  | 4.59  |
| Extra Trees            | 3.74  | 4.69  |
| Support Vector Regressor | 3.55 | 4.58  |
| Gradient Boosted       | 3.57  | 4.50  |
| **Baseline**           | 3.79  | 4.83  |

> ✅ **Best Model**: Linear Regression

---

## 🔮 Conclusion

The Linear Regression model achieved the best results with the lowest MAE and RMSE, making it the most reliable choice for this dataset. The project emphasizes the predictive power of earlier grades (G1, G2) and parental education.

---

## 🚀 Future Work

- Incorporate external educational or socioeconomic datasets
- Apply advanced techniques like:
  - Neural Networks
  - XGBoost / LightGBM
- Perform error analysis and refine feature engineering
- Deploy a web app or dashboard for grade prediction

---

## 🙏 Acknowledgments

This project utilizes the open dataset from a Portuguese secondary school. Special thanks to the contributors for providing such valuable data for research and educational purposes.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

Let me know if you want a version of this as a downloadable `README.md`, or if you'd like help generating visuals or packaging it for GitHub!
