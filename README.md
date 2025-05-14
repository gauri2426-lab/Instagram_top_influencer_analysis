# Instagram Influencer Engagement Analysis

## 📌 Objective

The goal of this project is to explore Instagram influencer data to:
- Understand the relationship between followers and engagement rates.
- Identify key factors influencing influencer performance.
- Build a machine learning model to predict influencer engagement.
- Provide actionable recommendations for marketers and influencer strategists.

---

## 📂 Data Overview

The dataset includes metrics from Instagram influencers, covering:
- **Follower count**
- **Engagement metrics** (likes, comments, engagement rates over time)
- **Content volume** (number of posts)
- **Geographic information**
- **Derived features** (e.g., likes per 1k followers)

It represents a wide variety of account sizes, from nano to mega influencers.

---


## 📓 Exploratory Data Analysis

Included in the `ipynb` file, the EDA:
- Visualizes the inverse relationship between follower size and engagement.
- Highlights outliers—high-performing accounts across follower tiers.
- Explores correlation across all numerical variables.
- Assesses distribution of engagement across countries and ranks.

---

## 🔍 Modeling Approach

We developed a feature importance model using tree-based ensemble methods. The most influential predictors of engagement include:
- **Rank**
- **Follower count**
- **Likes per 1,000 followers**
- **60-day engagement rate**
- **Country indicators**

The model was optimized to support strategic influencer selection, balancing engagement quality with audience reach.

---

## 📌 Key Findings

- **Inverse Relationship**: Engagement rate generally decreases as follower count grows.
- **Micro-influencer Advantage**: Smaller accounts often show significantly higher engagement.
- **Rank and Quality Metrics** are stronger predictors than follower count alone.
- **Country Influence**: Geography plays a role in engagement dynamics, especially in niche markets.
- **High-performing Outliers** are valuable for high-ROI campaigns.

---

## 🔜 Next Steps

- Implement more granular engagement metrics (e.g., video views, saves).
- Add sentiment analysis on content or captions.
- Fine-tune models using cross-validation and real campaign performance data.
- Integrate time-series analysis to forecast future engagement trends.

---

## ⚙️ Requirements

Create a virtual environment and install the dependencies with:

```bash
pip install -r requirements.txt
````

Dependencies include:

* Python 3.9+
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* xgboost
* plotly
* jupyter

---

## 👤 Author

Gauri Badhe

