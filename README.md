# 🏋️ Fitness Tracker — Activity Logger & Analyzer

A Python-based Fitness Tracking application built using OOP and Data Analysis libraries — log activities, analyze performance, and visualize fitness trends using real data. Built as a practical exam project combining Object-Oriented Programming with Data Analysis.

---

## 📌 Project Overview

This project simulates a real-world fitness tracker that allows users to log workout activities, store data in a structured format, perform statistical analysis, and generate insightful visualizations — all powered by Python's core data science stack.

---

## 🚀 Features

| Feature | Description |
|---|---|
| Activity Logger | Log activity type, duration, and calories burned with auto timestamp |
| Data Storage | Store all activities in a Pandas DataFrame |
| CSV Export | Save tracked data to `fitness_activities.csv` |
| Statistical Analysis | Mean, total, max calories and duration per activity |
| Data Visualization | Bar charts, line plots, and correlation heatmap |
| Correlation Analysis | Heatmap to find relationship between duration and calories |

---

## 🛠️ Tech Stack

- **Language:** Python 3.13
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, datetime
- **Concepts:** OOP (Class & Methods), EDA, Data Visualization, CSV Export
- **Tool:** Jupyter Notebook

---

## 📁 Project Structure

```
fitness-tracker/
│
├── Fitness_Tracker.ipynb     # Main Jupyter Notebook
├── fitness_activities.csv    # Generated activity dataset
└── README.md                 # Project documentation
```

---

## ▶️ How to Run

1. Clone the repository
```bash
git clone https://github.com/ravindra-data/fitness-tracker.git
```

2. Install dependencies
```bash
pip install numpy pandas matplotlib seaborn
```

3. Open the notebook
```bash
jupyter notebook Fitness_Tracker.ipynb
```

---

## 📊 Dataset Columns

| Column | Description |
|---|---|
| `date` | Date of activity (auto-generated) |
| `activity_type` | Type of workout (Running, Cycling, etc.) |
| `duration` | Duration in minutes |
| `calories` | Calories burned |

---

## 💡 What I Learned

- Designing a class-based fitness tracker using OOP
- Logging real-time data with `datetime` timestamps
- Storing and manipulating activity data using Pandas DataFrame
- Performing EDA on fitness data — totals, averages, trends
- Creating correlation heatmaps using Seaborn
- Exporting analyzed data to CSV using `to_csv()`

---
