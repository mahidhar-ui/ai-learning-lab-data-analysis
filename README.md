# ai-learning-lab-data-analysis
Data cleaning and EDA on AI Learning Lab student dataset using Python, Pandas, and Seaborn
# 🎓 AI Learning Lab — Data Cleaning & Analysis

## 📌 Project Overview
Performed data cleaning and exploratory data analysis (EDA) 
on a student performance dataset from an AI Learning Lab.

## 🛠️ Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn

## 📊 What This Project Does
- Removed duplicates and handled missing values
- Standardized categorical columns (attendance, topic, etc.)
- Validated score ranges (0–100) and filled nulls with mean/median
- Engineered a `total_score` and `performance_level` feature
- Visualized average scores by topic and performance distribution

## 📁 Files
| File | Description |
|------|-------------|
| `cleaned_ai_.ipynb` | Main analysis notebook |
| `ai_learning_lab.csv` | Raw dataset |
| `cleaned_ai_learning_lab.csv` | Cleaned output dataset |

## 📈 Key Insights
- Scored students into: Excellent / Good / Average / Bad
- Analyzed performance by batch and topic
- Identified students needing academic support
