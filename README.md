# 📊 IPL Data Analysis Dashboard (Power BI)

## 🚀 Project Overview
This project analyzes Indian Premier League (IPL) data (2008–2017) to uncover insights into player performance, team success, and match trends using Power BI.

---

## 📌 Introduction
The dataset consists of two main tables:

- **Matches Table** – Contains match-level data (venue, teams, winner, date)
- **Deliveries Table** – Contains ball-by-ball data (batsman, bowler, runs, dismissals)

These tables are connected using a **one-to-many relationship (Matches → Deliveries via `id`)**.

The dashboard enables **interactive analysis** where users can filter by season or team to explore trends and performance.

---

## 🎯 Objective
- Analyze player and team performance  
- Identify top batsmen and bowlers  
- Track match trends across seasons  
- Provide interactive insights using slicers  

---

## ⚙️ Methodology

### 🧹 Data Preparation
- Used historical IPL dataset (2008–2017)
- Handled missing values (e.g., city data)
- Standardized columns for consistency

### 🔗 Data Modeling
- Created relationship between `matches` and `deliveries`
- Built KPIs using DAX:
  - Total Runs
  - Total Wickets
  - Fours & Sixes
  - Centuries & Half-Centuries

---

## 📊 Dashboard Features

- Season & Team slicers  
- KPI cards (Runs, Matches, Teams, Centuries)  
- Orange Cap (Top Batsman)  
- Purple Cap (Top Bowler)  
- Toss decision analysis  
- Team & city performance charts  

👉 As seen in your dashboard (page 7 of your PDF), it includes:
- Top batsmen & bowlers  
- Wins by team & city  
- Season trends (runs over years)  

---

## 📈 Key Insights

- Peak scoring observed around **2012–2013**
- Identified top players like **David Warner (Orange Cap)** and **DJ Bravo (Purple Cap)**
- Teams show strong home advantage in certain cities
- Toss decisions show strategic preference (bat vs field)

---

## 🎯 Business Value

This dashboard helps:
- Teams analyze performance trends  
- Coaches identify key players  
- Analysts understand match strategies  
- Fans explore IPL statistics interactively  

---

## 🛠️ Tools Used

- Power BI  
- DAX  
- Data Modeling  
- Excel (for dataset preparation)

---

## ⚠️ Note

Due to dataset and file limitations, raw data files and Power BI (.pbix) file are not included.  
This project focuses on **dashboard design, data modeling, and insights extraction**.

---
