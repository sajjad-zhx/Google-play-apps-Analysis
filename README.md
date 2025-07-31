# Google Play Store Apps Analysis

## Project Overview
This project performs an end-to-end analysis of **Google Play Store Apps**, including:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Sentiment Analysis of user reviews
- Predictive modeling of app ratings
- Interactive dashboards with **Power BI**

The goal is to **understand factors affecting app ratings and popularity**.

---

## Dataset
- **Source:** [Kaggle - Google Play Store Apps](https://www.kaggle.com/lava18/google-play-store-apps)
- **Files Used:**
  - `googleplaystore.csv` (main dataset)
  - `googleplaystore_user_reviews.csv` (user review dataset)

---

## 🛠️ Tools & Libraries
- Python (Jupyter Notebook)
  - `pandas`, `numpy` – Data handling
  - `matplotlib`, `seaborn` – Visualization
  - `textblob`, `wordcloud` – Sentiment Analysis
  - `scikit-learn` – Machine Learning
- Power BI – Interactive dashboard

---

## 📈 Key Steps
1. **Data Cleaning**
   - Converted size to MB (`30M → 30.0`)
   - Removed invalid price strings (`$0.99 → 0.99`)
   - Created `Sentiment_Polarity` from reviews
2. **Exploratory Data Analysis**
   - Rating distributions, installs by category
   - Size & price vs. ratings
3. **Sentiment Analysis**
   - WordClouds for positive and negative reviews
   - Polarity scoring with TextBlob
4. **Predictive Modeling**
   - Random Forest Regressor for app rating prediction
   - Achieved **R² ≈ 0.486**
5. **Power BI Dashboard**
   - 3 Pages: Overview, Sentiment, Pricing & Performance

---

## 📊 Dashboard Preview
![Dashboard Preview](images/dashboard_preview.png)

---

## 📄 Results & Insights
- **Free apps dominate**, but paid apps do not always get higher ratings.
- **Sentiment correlates moderately** with app ratings.
- **Regular updates** often lead to higher ratings.
- **Model explains ~48%** of rating variance with 4 features.

---

## 📂 Project Structure
