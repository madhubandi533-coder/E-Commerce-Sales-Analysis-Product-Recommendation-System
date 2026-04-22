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

Source: [UCI Machine Learning Repository — Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)

Used a historical e-commerce dataset with 541K+ transactions, provided during internship and based on a public retail dataset.

#### Tools

- Python – Core programming language used for data analysis and modeling
- Jupyter Notebook / Google Colab – Environment for development, analysis, and visualization
- Pandas – Data cleaning, transformation, and handling large datasets
- NumPy – Numerical computations and array operations
- Matplotlib – Basic data visualization and plotting
- Seaborn – Advanced visualizations (heatmaps, trends, distributions)

#### Key Insights and Results

Key findings from the analysis include:
- UK contributed ~85% of total revenue (£7.3M of £8.9M total)
- Peak sales in November 2011 — £1.16M revenue in a single month
- Top product: PAPER CRAFT, LITTLE BIRDIE — 80,995 units sold
- Top 10 customers generated ~15% of total revenue
- 2.78M unique product pairs identified across 18,532 invoices
- Most co-purchased pair: JUMBO BAG PINK POLKADOT + JUMBO BAG RED RETROSPOT (544 times)

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


#### How to Run the Project

1. **Clone the repository**
```bash
git clone https://github.com/madhubandi533/online_retail_recommendation-System.git
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Add the dataset**
- Place `OnlineRetail.xlsx` in the `data/` folder  
- *(Dataset not included — download from [UCI Repository](https://archive.ics.uci.edu/dataset/352/online+retail))*

4. **Open the notebook**
```bash
jupyter notebook notebooks/online_retail_recommendation.ipynb
```

5. **Run the notebook**
- Click: `Kernel → Restart & Run All`
