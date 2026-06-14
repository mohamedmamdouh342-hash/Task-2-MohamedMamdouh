# ⚽ European Football Player Performance Analytics & Prediction System
### Season 2025/2026 — Top 5 Leagues | Decode Labs Data Science Internship

![Python](https://img.shields.io/badge/Python-3.10-blue) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange) ![sklearn](https://img.shields.io/badge/scikit--learn-ML-green) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Project Overview

End-to-end football data science project analyzing **2,363 players** (after cleaning) across Europe's Top 5 leagues for the 2025/26 season. Covers all 5 internship tasks with **20 professional visualizations** and **5 machine learning models**.

---

## 📁 Project Structure

```
Football-Player-Analytics/
├── data/
│   └── players_data-2025_2026.csv        ← 2,839 raw players × 102 features
├── notebooks/
│   └── Football_Analytics_2025_26.ipynb  ← Complete end-to-end notebook
├── visuals/                              ← 24 charts at 150 DPI
├── models/
│   └── all_models.pkl                    ← All 5 trained models
├── reports/
│   └── Football_Analytics_Report.pdf     ← Full project PDF report
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📊 Dataset

| Property | Value |
|---|---|
| Raw players | 2,839 |
| After cleaning | 2,363 |
| Raw columns | 102 |
| Columns after cleaning | 66 |
| Leagues | Premier League · La Liga · Bundesliga · Serie A · Ligue 1 |
| Season | 2025/26 |

---

## 🏆 Key Findings

| Finding | Detail |
|---|---|
| Top Scorer | Harry Kane — 36 goals (Bayern Munich) |
| Top Assister | Bruno Fernandes — 21 assists (Manchester United) |
| Most Attacking League | Bundesliga — 2.249 avg goals/player |
| Most Defensive League | Serie A — 1.750 avg goals/player |
| Peak Performance Age | 26–28 years (2.427 avg goals/player) |
| GK Classifier | 100% accuracy — goalkeeper stats are uniquely identifiable |

---

## 🤖 Models

| Model | Target | Best Algorithm | Score |
|---|---|---|---|
| Role Classifier | Position (GK/DF/MF/FW) | Random Forest | 76.11% accuracy |
| Forward Model | Goals scored | Random Forest | R² = 0.934 |
| Midfielder Model | Assists | Ridge Regression | R² = 0.514 |
| Defender Model | Defensive Score (TklW+Int) | Ridge Regression | R² = 0.777 |
| Goalkeeper Model | Save Percentage | Gradient Boosting | R² = 0.751 |

---

## 📈 Visualizations — 20 Charts

| Charts | Description |
|---|---|
| 1–10 | Standard: top scorers, assists, distributions, correlations, position stats |
| 11 | Shooting Efficiency Quadrant — who is accurate AND clinical? |
| 12 | Goal-Scoring Aging Curve — at what age does each position peak? |
| 13 | League DNA Radar — statistical fingerprint of each league |
| 14 | Player Value Map — rate vs volume, elite workhorses |
| 15 | Defensive Workrate Heatmap — league × position demands |
| 16 | Underplayed Gems — high per-90 rate, low minutes |
| 17 | Discipline Analysis — cards by league and position |
| 18 | Goals vs +/- Impact — do top scorers help teams win? |
| 19 | GK Workload vs Performance Matrix |
| 20 | Performance Score Rankings — best per position |

---

## 🚀 How to Run

```bash
git clone https://github.com/mohamedmamdouh342-hash/decode-labs-data-science-internship.git
cd decode-labs-data-science-internship
pip install -r requirements.txt
jupyter notebook notebooks/Football_Analytics_2025_26.ipynb
```

> Place `players_data-2025_2026.csv` in the `data/` folder before running.

---

## 🛠️ Tech Stack

`Python 3.10` · `pandas` · `numpy` · `matplotlib` · `seaborn` · `scikit-learn` · `Jupyter`

---

*Decode Labs Data Science Internship | Season 2025/26 | Intern: Mohamed Mamdouh*
