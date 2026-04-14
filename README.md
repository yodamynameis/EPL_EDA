# 📊 English Premier League (2000–2025) – Exploratory Data Analysis

## 🔍 Overview
This project presents a comprehensive **Exploratory Data Analysis (EDA)** of English Premier League (EPL) match data spanning **25 seasons (2000–2025)**.  

The objective is to uncover patterns in team performance, scoring trends, and disciplinary behavior using data-driven insights and visualizations.

---

## 🎯 Objectives
- Analyze **goal-scoring trends** across seasons  
- Compare **home vs away team performance**  
- Study **discipline metrics** (yellow/red cards)  
- Identify **team-level patterns and anomalies**  
- Derive insights useful for **football analytics and scouting**

---

## 📁 Dataset
- Matches from EPL seasons **2000–2025**
- Includes:
  - Match results (goals, outcomes)
  - Team statistics (shots, corners, fouls)
  - Discipline data (yellow & red cards)

---

## ⚙️ Tech Stack
- **Python**
- **Pandas** → data manipulation  
- **NumPy** → numerical operations  
- **Matplotlib & Seaborn** → data visualization  

---

## 📊 Key Analysis Performed

### ⚽ Goal Analysis
- Distribution of goals scored
- Home vs away scoring trends
- High-scoring vs low-scoring matches

### 🏠 Home Advantage Study
- Win/draw/loss distribution
- Impact of playing at home

### 🟥 Discipline Analysis
- Yellow & red card trends
- Team-wise aggression comparison  
- **Aggression Delta (Away − Home cards per game)**

### 📈 Team Insights
- Most consistent teams
- Aggressive vs disciplined teams
- Performance variation across seasons

---

## 🔥 Key Insights
- Strong **home advantage trend** observed across seasons  
- Certain teams consistently show **higher aggression levels**  
- Away teams tend to receive **more cards on average**  
- Goal distributions highlight evolving attacking trends  

---

## 📌 Visualizations
- Bar plots, histograms, and comparative charts  
- Custom visualizations for:
  - Aggression Delta  
  - Team comparisons  
  - Seasonal trends  

---

## 🚀 How to Run
```bash
git clone https://github.com/your-username/epl-eda.git
cd epl-eda
pip install -r requirements.txt
jupyter notebook
