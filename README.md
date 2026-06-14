# 🎬 Netflix Content Data Analysis

A beginner-friendly **Data Analytics Mini Project** using Python — exploring Netflix's content library through data cleaning, analysis, and visualization.

---

## 📁 Project Structure

```
Python_Mini_Project/
│
├── data_analytics_mini_project_.ipynb   # 📊 Main notebook — Netflix analysis
├── python_basics.ipynb                 # 🐍 Python basics practice
├── python_basics.py                    # 🐍 Python basics script
├── python_numpy.ipynb                  # 🔢 NumPy practice
└── python_pandas.ipynb                 # 🐼 Pandas practice
```

---

## 📌 Project Overview

This project analyzes the **Netflix Movies and TV Shows** dataset to uncover trends and patterns in Netflix's content library.

**Dataset:** [Netflix Shows — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
**Records:** 8,807 titles | **Features:** 12 columns

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| Pandas | Data loading & cleaning |
| Matplotlib | Visualizations |
| Seaborn | Styled charts |
| Jupyter Notebook | Development environment |

---

## 🔍 What's Covered

### Step 1 — Setup
- Import libraries
- Load the dataset

### Step 2 — Explore (EDA)
- Check shape, columns, data types
- Identify missing values

### Step 3 — Data Cleaning
- Fill missing `director`, `cast`, `country` with `"Unknown"`
- Drop rows with missing `date_added`, `rating`, `duration`
- Convert `date_added` to proper datetime
- Extract `year_added` and `month_added` columns

### Step 4 — Analysis
- Movies vs TV Shows distribution
- Top 10 countries producing content
- Content growth trend over the years
- Top 10 genres
- Rating distribution
- Best months for content addition

### Step 5 — Visualizations
- 🥧 Pie chart — Movies vs TV Shows
- 📊 Bar chart — Top 10 Countries
- 📈 Line chart — Content Added Per Year
- 📊 Bar chart — Top 10 Genres
- 📊 Bar chart — Rating Distribution
- 📊 Bar chart — Monthly Content Addition

---

## 📊 Sample Insights

- Netflix has significantly more **Movies** than TV Shows
- **United States** dominates content production
- Netflix content additions peaked around **2019–2020**
- Most common rating is **TV-MA** (mature audiences)
- **International Movies** and **Dramas** are the top genres

---

## 🚀 How to Run

1. Clone the repo
   ```bash
   git clone https://github.com/achathwara/Python_Mini_Project.git
   cd Python_Mini_Project
   ```

2. Install dependencies
   ```bash
   pip install pandas matplotlib seaborn
   ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) and place `netflix_titles.csv` in the project folder

4. Open the notebook
   ```bash
   jupyter notebook data_anlytics_mini_project_.ipynb
   ```

---

## 👨‍💻 Author

**Achala Dasanayake** — Undergraduate, Faculty of Science, University of Peradeniya  
📍 Sri Lanka
