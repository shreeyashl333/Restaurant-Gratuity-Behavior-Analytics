# 🧾 Restaurant Tipping Insights Dashboard

An interactive data dashboard that explores tipping behavior in a restaurant setting. Built using Python, Plotly, and Pandas, this project uncovers actionable insights on how factors like party size, day of the week, and meal time influence tipping behavior.

---

## 📊 Project Overview

This project uses the well-known [`tips`](https://github.com/mwaskom/seaborn-data/blob/master/tips.csv) dataset from Seaborn to perform exploratory data analysis (EDA) and visualize key trends in restaurant gratuity behavior.

### 💼 Key Objectives
- Understand how party size impacts total and per-person tipping
- Compare tipping patterns across different days and meal times
- Identify the most profitable day/time combinations for tips
- Build a clean and interactive dashboard using Plotly

---

## 📌 Dataset

- Source: `seaborn.load_dataset('tips')`
- Records: 244
- Features: total bill, tip amount, gender, smoking status, day, time, party size

---

## 📈 Features & Visualizations

| 📍 KPI Metrics                            | ✅ Included |
|------------------------------------------|-------------|
| Total tips collected                     | ✔️          |
| Average tip per person                   | ✔️          |
| Best tipping day and time                | ✔️          |

| 📊 Charts                                 | 📋 Description                            |
|------------------------------------------|-------------------------------------------|
| Bar Chart (Avg Tip by Day)               | Compare tipping averages by weekday       |
| Scatter Plot (Tip vs Party Size)         | Visualize correlation between party size and tip amount |
| Box Plot (Tip Per Person by Day)         | Examine tip distributions per person      |
| Heatmap (Avg Tip by Day & Time)          | Analyze combined day-time tipping behavior |

---

## 🛠️ Tech Stack

- Python
- Pandas
- Plotly Express
- Seaborn (for exploration)
- Google Colab

---

## 📎 Project Highlights

- Built a reusable and extensible dashboard for quick tipping behavior analysis
- Demonstrated real-world analytics thinking with business-oriented KPIs
- Saved outputs as interactive HTML and printable PDF dashboard formats

---

