# 🎬 Netflix Content Analysis — Exploratory Data Analysis (EDA)

> **Uncovering patterns, trends, and strategies behind Netflix's 8,000+ title library using Python-based data analysis.**

---

## 📌 Project Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the Netflix dataset to extract meaningful insights about content distribution, growth trends, genre popularity, and audience targeting strategies.

The analysis answers real business questions like:
- How has Netflix's content library grown over the years?
- Which countries and genres dominate the platform?
- What audience segments does Netflix primarily target?

---

## 📊 Dataset

**Source:** [Netflix Titles Dataset — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

| Feature | Description |
|---------|-------------|
| `title` | Name of the content |
| `type` | Movie or TV Show |
| `director` | Director name |
| `cast` | Lead actors |
| `country` | Country of production |
| `date_added` | Date added to Netflix |
| `release_year` | Original release year |
| `rating` | Audience rating (TV-MA, PG, etc.) |
| `duration` | Runtime (minutes) or seasons |
| `listed_in` | Genre categories |

---

## 🎯 Objectives

- 📽️ Analyze distribution of **Movies vs TV Shows**
- 📈 Track **Netflix content growth** over the years
- 🎭 Identify the **most popular genres**
- ⏱️ Analyze **movie duration** and **TV show season counts**
- 🌍 Find **top contributing countries**
- 👥 Study **content ratings** and audience targeting

---

## 🔍 Key Insights

| # | Insight |
|---|---------|
| 1 | 🎬 **Movies make up ~70%** of Netflix's catalog, outnumbering TV Shows significantly |
| 2 | 📈 **Content additions surged after 2016**, peaking around 2019 — reflecting Netflix's global expansion phase |
| 3 | ⏱️ **Most movies run between 90–120 minutes**, aligning with standard feature-film length |
| 4 | 📺 **~70% of TV Shows have only 1 season**, suggesting Netflix tests new shows before renewal |
| 5 | 🇺🇸 **USA leads content production**, followed by India 🇮🇳 and the United Kingdom 🇬🇧 |
| 6 | 🎭 **International Movies, Dramas, and Comedies** are the top 3 genres on the platform |
| 7 | 🔞 **TV-MA and TV-14 are the most common ratings**, indicating a focus on mature and teenage audiences |

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=flat&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical_Plots-4c72b0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter)

---

## 📈 Visualizations Included

- 📊 Bar chart — Movies vs TV Shows distribution
- 📅 Line chart — Content added per year (growth trend)
- 🌍 Horizontal bar chart — Top 10 countries by title count
- 🎭 Bar chart — Top 15 genres
- ⏱️ Histogram — Movie duration distribution
- 📺 Count plot — TV Show season distribution
- 🔞 Bar chart — Content ratings breakdown
- 🗺️ Heatmap — Missing values analysis

---

## 📁 Project Structure

```
Netflix-EDA/
│
├── netflix_analysis.ipynb    # Main analysis notebook
├── netflix_titles.csv        # Dataset
└── README.md                 # Project documentation
```

---

## ⚙️ Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Netflix-EDA.git
cd Netflix-EDA
```

### 2️⃣ Install Dependencies

```bash
pip install pandas matplotlib seaborn jupyter
```

### 3️⃣ Launch Notebook

```bash
jupyter notebook netflix_analysis.ipynb
```

---

## 🧠 Skills Demonstrated

| Skill | Detail |
|-------|--------|
| **Data Cleaning** | Handled missing values, parsed dates, split multi-value columns |
| **Feature Engineering** | Extracted year/month from dates, split genre lists |
| **Statistical Analysis** | Distribution analysis, frequency counts, correlation |
| **Data Visualization** | 8+ chart types using Matplotlib & Seaborn |
| **Business Thinking** | Translated data patterns into actionable insights |

---

## 🚧 Challenges & Solutions

| Challenge | Solution |
|-----------|----------|
| Multiple genres stored in single column | Used `str.split()` + `explode()` to normalize |
| Missing values in `director`, `cast`, `country` | Analyzed null patterns, filled or excluded based on context |
| Inconsistent `duration` format (mins vs seasons) | Separated Movies and TV Shows before parsing |

---

## 🎯 Future Improvements

- 📊 Build **interactive dashboards** using Plotly / Dash
- 📅 Perform **time-series analysis** on genre trends by year
- 🤖 Build a **content-based recommendation system**
- ☁️ Deploy dashboard on **Streamlit Cloud**

---

## 🧠 One-Line Summary (For Resume / Interview)

> *"Performed end-to-end EDA on Netflix's 8,000+ title dataset using Python, uncovering content growth trends, genre dominance, and audience targeting patterns through 8+ statistical visualizations."*

---

## 👨‍💻 Author

**Abhinav Chaudhary**

[![GitHub](https://img.shields.io/badge/GitHub-abhichiku18-black?style=flat&logo=github)](https://github.com/abhichiku18)

---

## ⭐ Support

Found this helpful? Give it a **⭐ star** on GitHub!
