### Online Retail Analytics & Recommendation System 

#### Table of contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Key Insights and Results](#key-insights-and-results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

#### Project Overview

Built a multi layered recommendation system on 541K+ transactions using co-occurrence, country level popularity, and temporal trends. Identified key business insights such as top performing regions (UK) and peak sales periods (November) to support cross selling and inventory optimization.

#### Data Sources

Dataset: Online Retail Dataset

Used a historical e-commerce dataset with 541K+ transactions, provided during internship and based on a public retail dataset.

#### Tools

- Python – Core programming language used for data analysis and modeling
- Jupyter Notebook / Google Colab – Environment for development, analysis, and visualization
- Pandas – Data cleaning, transformation, and handling large datasets
- NumPy – Numerical computations and array operations
- Scikit-learn (sklearn) – Machine learning models (Logistic Regression, Random Forest) and preprocessing
- Imbalanced-learn (SMOTE) – Handling class imbalance in the dataset
- Matplotlib – Basic data visualization and plotting
- Seaborn – Advanced visualizations (heatmaps, trends, distributions)

#### Key Insights and Results

Key findings from the analysis include:
- UK contributed the highest revenue
- Peak sales observed in November
- Identified frequently co-purchased products
- Built multi-layer recommendation models (global, regional, temporal)
- Derived insights for cross-selling and inventory optimization

#### Recommendations

- Since UK is bringing most of the revenue, the company should focus more on that region (offers, stock, marketing etc.)
- Sales are highest in November, so it makes sense to prepare inventory and run campaigns before that time
- Products that are often bought together can be shown as suggestions to increase order value
- Different countries have different popular items, so recommendations shouldn’t be the same for everyone

#### Limitations

- The data is from 2010–2011, so it may not fully reflect current trends or customer behavior
- There isn’t much detailed customer information, so recommendations are based on general purchase patterns, not individual preferences
- The system is not real-time — it works on a fixed dataset rather than live user activity
- New or less popular products may not get recommended often since the system depends on past purchase frequency (cold start issue)
