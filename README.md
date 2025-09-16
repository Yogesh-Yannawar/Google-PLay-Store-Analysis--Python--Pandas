## 📊 Google Play Store Analysis (Python & Pandas)

# 🚀 Project Overview

The Google Play Store Analysis project explores app data from the Google Play Store using Python and Pandas.
It focuses on data cleaning, exploratory data analysis (EDA), and visualization to uncover insights about apps, categories, ratings, reviews, installs, and more.

---

# 📊 Dataset

The dataset googleplaystore.csv contains the following key attributes:

App → App name

Category → Category of the app (e.g., GAME, BUSINESS)

Rating → User rating (1–5 scale)

Reviews → Number of user reviews

Installs → Number of installs (approximate)

Size → App size (MB, KB, or variable)

Price → App price (free or paid)

Type → Free or Paid

Content Rating → Target audience (Everyone, Teen, Mature 17+)

Genres → Specific genre(s) of the app

---

# 🔍 Key Analysis Performed

## Data Cleaning

Handling missing values

Converting data types

Removing duplicates and anomalies

## Exploratory Data Analysis

Distribution of apps across categories

Most popular app categories by installs & reviews

Highest rated apps

Relationship between ratings, installs, and reviews

Free vs Paid app comparisons

--- 

## Contents

# File	                                                    Description
googleplaystore.csv	                      The raw dataset. Contains details of Google Play Store apps (various attributes such as category, ratings, reviews, size, installs, etc.).
Google Play Store.ipynb	                  Jupyter Notebook where the data is analyzed. Includes data cleaning, exploratory data analysis, visualizations, and summary of findings.
Google Play StoreQuestions.txt	          A text file containing questions / prompts related to the dataset, likely used to guide analysis.

---
## Requirements / Dependencies

Python

Pandas

Jupyter Notebook

---

## ⚙️ Installation & Usage

**Clone the repository:**
```bash
git clone https://github.com/Yogesh-Yannawar/Google-PLay-Store-Analysis--Python--Pandas.git
cd Google-PLay-Store-Analysis--Python--Pandas
```

**2. Install required libraries:**  
```bash
pip install pandas matplotlib seaborn jupyter
```


**3. Open the Jupyter Notebook:**  
```bash
jupyter notebook "Google Play Store.ipynb"
```


