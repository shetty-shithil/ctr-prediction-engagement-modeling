# 📊 CTR Prediction & Engagement Modeling for Social Media Ads

## 📌 Project Overview

This project analyzes **social media advertisement performance** across platforms such as **Facebook** and **Instagram**, focusing on **Click-Through Rate (CTR)**, **user engagement**, and **conversion behavior**. Using a combination of **exploratory data analysis, feature engineering, and predictive modeling**, we identify the factors that drive meaningful user interactions and provide actionable insights for ad optimization.

The analysis supports **data-driven decision making** for advertisers by understanding how **ad characteristics, audience demographics, timing, and device context** influence engagement and conversion outcomes.

---

## 🎯 Research Questions

1. **How can we predict the best combination of day of week and device type to maximize conversions in each country?**
2. **Which ad characteristics, demographic factors, and device contexts are the strongest predictors of user engagement?**
3. **Which audience segments generate high impressions but low conversions, indicating inefficient ad spend?**
4. **Does a data-driven engagement score predict conversions better than traditional CTR?**
5. **How does CTR vary across different combinations of platform, ad format, day of week, and device type?**

---

## 🧠 Methodology

### 1️⃣ Data Preparation & EDA
- Cleaned and validated the dataset
- Analyzed distributions, missing values, and categorical consistency
- Explored engagement patterns across demographics, platforms, devices, and time

### 2️⃣ Feature Engineering
- Created key performance metrics:
  - **CTR** = Clicks / Impressions
  - **CVR** = Conversions / Clicks
- Encoded categorical variables
- Constructed interaction features (e.g., **day × device**)
- Developed both **unsupervised (PCA-based)** and **supervised (model-based)** engagement scores

### 3️⃣ Modeling & Analysis
- **Logistic Regression** for conversion prediction
- **Tree-based models** for CTR analysis
- **Interaction modeling** to evaluate contextual effects
- **Segment-level analysis** to identify underperforming audiences
- Model evaluation using accuracy, AUC, log-loss, and interpretability of coefficients

### 4️⃣ Visualization & Interpretation
- Heatmaps, bar charts, interaction plots, and decision trees
- Focused on **interpretability and business relevance**
- Emphasized actionable insights rather than black-box predictions

---

## 📎 Dataset Source
Kaggle - Social Media Ad Dataset
https://www.kaggle.com/datasets/ziya07/social-media-ad-dataset
