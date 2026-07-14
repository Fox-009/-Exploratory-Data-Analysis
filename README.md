# 📊 Data Science & Analytics Projects

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0.3-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.24-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.1-11557c?logo=python&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.12.2-1279a6?logo=python&logoColor=white)](https://seaborn.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)

---

## 📌 About This Repository
This repository contains a collection of **Exploratory Data Analysis (EDA)** projects on real-world datasets. Each project focuses on cleaning raw data, uncovering patterns, and extracting insights using Python's data analysis stack — building the foundation for statistical reasoning and future machine learning work.

---

## ⭐ Repository Highlights
- 3 independent EDA projects across sports, survival analysis, and app-store data
- Consistent workflow: cleaning → univariate/bivariate analysis → visualization → insight extraction
- Every insight below is backed by an actual number pulled from the notebook — nothing rounded up or guessed
- Built entirely with Python's core data-analysis stack (no black-box tools)

---

## 🧠 Skills Demonstrated
- **Data Cleaning**: handling missing values, type conversion, deduplication
- **Exploratory Analysis**: groupby aggregations, cross-tabulations, correlation checks
- **Data Visualization**: Matplotlib & Seaborn (bar charts, histograms, heatmaps, count plots)
- **Statistical Reasoning**: survival rates, win-rate percentages, distribution analysis
- **Notebook Documentation**: structured, readable Jupyter notebooks with markdown commentary

*(This repo is EDA-focused — no ML models are built here yet. That's the planned next step, see Future Improvements.)*

---

## 🗂️ Projects

### 1️⃣ [IPL 2022 EDA](./IPL-EDA-2022/)
- **Description**: EDA on IPL 2022 match data (74 matches, 20 columns).
- **Key Insights**:
  - Toss winner wins **48.65%** of matches
  - Most teams chose to **field first** (59/74)
  - Top scorer: **Quinton de Kock (140 runs)**
  - Best bowling figures: **Jasprit Bumrah (5/10)**
  - Most-used venue: **Wankhede Stadium, Mumbai (21 matches)**
  - Most match wins: **Gujarat Titans (12 wins)**
- **Tech Stack**: Python, Pandas, NumPy, Matplotlib, Seaborn
- **Status**: ✅ Completed
- **Preview**: `assets/ipl_preview.png` *(placeholder — add a chart screenshot here)*

---

### 2️⃣ [Titanic EDA](./Titanic/)
- **Description**: EDA on the Titanic dataset to understand passenger demographics and survival patterns.
- **Key Insights**:
  - Overall survival rate: **38.4%**
  - Women had a **74%** survival rate vs. **19%** for men
  - 1st Class: **63%** survived vs. **24%** in 3rd Class
  - Best-surviving family size: **3 members (72.4% survived)**
  - Higher fare correlated with higher survival
  - Best combination: **Female + 1st Class → 96.8% survived**
- **Tech Stack**: Python, Pandas, Matplotlib, Seaborn
- **Status**: ✅ Completed
- **Preview**: `assets/titanic_preview.png` *(placeholder — add a chart screenshot here)*

---

### 3️⃣ [Play Store EDA](./Google%20playstore/)
- **Description**: EDA on Google Play Store apps to understand app trends and user preferences.
- **Key Insights**:
  - Free apps dominate (**93.1%** of all apps)
  - Average app rating: **4.19**
  - Most popular category: **Family**
  - Paid apps have slightly higher average ratings
  - No strong correlation found between app size and rating
- **Tech Stack**: Python, Pandas, NumPy, Matplotlib, Seaborn
- **Status**: ✅ Completed
- **Preview**: `assets/playstore_preview.png` *(placeholder — add a chart screenshot here)*

---

## 🔄 Workflow Followed
Each project in this repo follows the same structured process:
1. **Data Loading & Inspection** — check shape, dtypes, missing values
2. **Data Cleaning** — handle nulls, fix types, remove duplicates
3. **Univariate Analysis** — distributions of individual columns
4. **Bivariate/Multivariate Analysis** — relationships between variables
5. **Visualization** — charts to support each insight
6. **Insight Summary** — key findings documented per project

---

## 🛠️ Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python 3.10 | Core programming language |
| Pandas | Data manipulation & cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Interactive development environment |

---

## 📂 Repository Structure
```
Exploratory-Data-Analysis/
├── IPL-EDA-2022/
│   ├── IPL_2022.ipynb
│   └── IPL.csv
├── Titanic/
│   ├── Titanic.ipynb
│   └── Titanic-Dataset.csv
├── Google playstore/
│   ├── Google_playstore.ipynb
│   └── googleplaystore.csv
├── assets/
│   └── (preview images go here)
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup

```bash
git clone https://github.com/Fox-009/-Exploratory-Data-Analysis.git
cd "-Exploratory-Data-Analysis"
pip install -r requirements.txt
jupyter notebook
```
Then open any `.ipynb` file from its project folder to view the analysis.

---

## 🚀 Future Improvements
- Add a machine learning model on top of the Titanic dataset (survival prediction)
- Add feature engineering steps for the Play Store dataset
- Add automated data-cleaning scripts (`.py`) alongside notebooks
- Add unit tests for reusable analysis functions

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).

---

## 📬 Connect
- GitHub: [@Fox-009](https://github.com/Fox-009)
- LeetCode: [fox-009](https://leetcode.com/fox-009)
