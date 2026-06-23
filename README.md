# 🏏 IPL Data Analysis (2008–2019)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow)

## 📌 Project Overview

This project performs an in-depth analysis of the Indian Premier League (IPL) from 2008 to 2019 using ball-by-ball and match-level datasets.

The objective is to extract meaningful insights from historical IPL data through data cleaning, preprocessing, feature engineering, exploratory data analysis (EDA), and visualization techniques.

---

## 🎯 Objectives

- Analyze IPL match and delivery datasets.
- Handle missing values and data inconsistencies.
- Perform feature engineering.
- Discover trends in batting, bowling, and team performances.
- Analyze toss decisions and match outcomes.
- Study venue-wise performance patterns.
- Generate visual insights using charts and graphs.

---

## 📊 Dataset Information

| Dataset | Records |
|----------|----------|
| Matches | 756 |
| Deliveries | 179,078 |
| Seasons Covered | 12 |
| Years | 2008–2019 |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- JSON
- CSV

---

## 📂 Project Structure

```text
IPL-Mini-Project-2/
│
├── README.md
├── insights.json
│
├── data/
│   ├── matches.csv
│   └── deliveries.csv
│
├── notebook/
│   └── IPL_Analysis.ipynb
│
├── charts/
│   ├── 05_toss_impact.png
│   ├── 05b_toss_by_season.png
│   ├── 06_top10_runs.png
│   ├── 06b_top3_dismissals.png
│   ├── 07_avg_runs_trend.png
│   ├── 07b_regression.png
│   ├── 08_venue_heatmap.png
│   └── 09_death_overs.png
│
├── report/
│   └── IPL_Mini_Project_2_Report.pdf
│
└── ppt/
    └── IPL_Mini_Project_2.pptx
```

---

## 📈 Key Findings

### 🔥 Top 5 Run Scorers

| Player | Runs |
|----------|----------|
| Virat Kohli | 5434 |
| Suresh Raina | 5415 |
| Rohit Sharma | 4914 |
| David Warner | 4741 |
| Shikhar Dhawan | 4632 |

---

### 🎯 Best Economy Bowlers

| Bowler | Economy |
|----------|----------|
| Anil Kumble | 6.58 |
| Muttiah Muralitharan | 6.70 |
| Rashid Khan | 6.73 |
| Sunil Narine | 6.75 |
| Daniel Vettori | 6.78 |

---

### 🏆 Team Performance Analysis

- Rajasthan Royals recorded the highest win percentage in 2008.
- Mumbai Indians emerged as the most successful franchise across seasons.
- Chennai Super Kings consistently maintained strong performances.

---

### 🪙 Toss Impact

| Decision | Win Percentage |
|------------|------------|
| Field First | 55.9% |
| Bat First | 45.7% |

Teams choosing to field first enjoyed a slight advantage.

---

### 📈 Scoring Trend

Average runs per match increased steadily across IPL seasons.

**Regression Analysis:** +3.59 runs per season

This indicates that IPL has become progressively more batting-friendly.

---

### 🏟️ Most Popular Venues

- Eden Gardens
- M Chinnaswamy Stadium
- Wankhede Stadium
- Feroz Shah Kotla
- Rajiv Gandhi International Stadium

---

## 📸 Visualizations

The project includes multiple visual analyses:

- Toss Impact Analysis
- Toss Trends by Season
- Top Run Scorers
- Dismissal Type Distribution
- Seasonal Run Trends
- Regression Trend Analysis
- Venue Heatmap Analysis
- Death Over Performance Analysis

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/IPL-Mini-Project-2.git
```

### Navigate to Project Folder

```bash
cd IPL-Mini-Project-2
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib jupyter
```

### Launch Notebook

```bash
jupyter notebook
```

Open:

```text
notebook/IPL_Analysis.ipynb
```

Run all cells to reproduce the analysis.

---

## 📚 Learning Outcomes

This project helped in understanding:

- Data Cleaning
- Missing Value Treatment
- Feature Engineering
- Exploratory Data Analysis
- Data Visualization
- Statistical Analysis
- Data Storytelling

---

## 🔮 Future Scope

- IPL Winner Prediction using Machine Learning
- Interactive Dashboard using Streamlit
- Real-Time IPL Analytics
- Advanced Player Performance Modeling
- Inclusion of IPL seasons after 2019

---

## 👨‍💻 Author

### Akhil Bedi

Data Science Student

Interested in:
- Data Analytics
- Machine Learning
- Artificial Intelligence
- History
- Problem Solving

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

