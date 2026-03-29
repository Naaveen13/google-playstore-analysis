# 📱 Google Play Store Data Analysis — Python EDA

Exploratory Data Analysis (EDA) on 10,000+ Android apps from the Google Play Store, answering 16 business questions using Python — uncovering trends in ratings, reviews, installs, categories, and free vs paid apps.

---

## 🎯 Project Overview

This project analyzes the Google Play Store dataset from Kaggle to understand the Android app market. It covers data cleaning, statistical analysis, and visualization to extract meaningful insights about app performance across different categories.

---

## ❓ Questions Answered

| # | Question |
|---|---|
| 1 | Total number of apps in Google Play Store |
| 2 | Total number of columns in the dataset |
| 3 | Shape of dataset (rows & columns) |
| 4 | Dataset info — datatypes, memory usage |
| 5 | Overall descriptive statistics |
| 6 | Total apps with "Astrology" in the title |
| 7 | Average app rating |
| 8 | Total number of unique categories |
| 9 | Which category has the highest average rating? |
| 10 | Total apps with 5-star rating |
| 11 | Average value of reviews |
| 12 | Total number of Free vs Paid apps |
| 13 | Which app has the maximum reviews? |
| 14 | Top 5 apps with highest reviews |
| 15 | Average rating of Free vs Paid apps |
| 16 | Top 5 apps with maximum installs |

---

## 🔑 Key Findings

| Insight | Finding |
|---|---|
| Average App Rating | **~4.17 / 5** |
| Total Unique Categories | **34** |
| App with Most Reviews | **Facebook** |
| Free vs Paid Split | **~92% Free apps** |
| Top Installed Apps | Google, YouTube, Facebook |
| Highest Rated Category | Events / Health & Fitness |

---

## 🛠️ Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 📁 Repository Structure

```
google-playstore-analysis/
│
├── notebooks/
│   └── Google_PlayStore_Analysis.ipynb   # Main analysis notebook (16 questions)
├── data/
│   └── googleplaystore.csv               # Dataset (download from Kaggle)
├── assets/                               # Visualization screenshots
├── .gitignore
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Naaveen13/google-playstore-analysis.git
   cd google-playstore-analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib jupyter
   ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps) and place it as `data/googleplaystore.csv`

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/Google_PlayStore_Analysis.ipynb
   ```

---

## 📂 Dataset

- **Source:** [Kaggle — Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)
- **Size:** ~10,000 apps
- **Key columns:** App, Category, Rating, Reviews, Size, Installs, Type, Price, Content Rating, Genres

---

## 📬 Contact

**Naveen Krishna Venigandla**  
📧 naveenkrishna.v13@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/naveen-krishna-324b341bb)
