# Zomato Bangalore Restaurants — EDA

Exploratory Data Analysis on the [Zomato Bangalore Restaurants dataset](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants) 

---

## Objective

Uncover patterns in Bangalore's restaurant ecosystem — including cuisine preferences, pricing, ratings, online ordering trends, and locality-wise distributions.

---

## Dataset

- **Source:** Kaggle — Zomato Bangalore Restaurants
- **Size:** ~51,000 restaurants
- **Key columns:** `name`, `location`, `cuisines`, `approx_cost(for two people)`, `rate`, `votes`, `online_order`, `book_table`, `listed_in(type)`

---

## Analysis Performed

**Data Cleaning**
- Handled missing values, stripped rating strings, converted cost to numeric

**Univariate Analysis**
- Rating distribution, cost distribution, top cuisines, restaurant type breakdown

**Bivariate & Multivariate Analysis**
- Rating vs. cost, online ordering vs. ratings, location-wise restaurant density, cuisine vs. average cost heatmaps

**Key Insights**
- Majority of restaurants offer online ordering; those that do tend to have higher ratings
- Most restaurants fall in the ₹200–600 cost range for two
- North Indian and Chinese cuisines dominate across localities
- BTM, Koramangala, and Indiranagar have the highest restaurant density

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data wrangling |
| Matplotlib / Seaborn | Visualizations |
| Jupyter Notebook | Analysis environment |

---

## Repository Structure

```
EDA_zomato-DataSet/
├── EDA on zomato dataset.ipynb   # Main analysis notebook
├── univariate_analysis.png        # Univariate plots
├── multivarient analysis.png      # Multivariate plots
├── key_insights.png               # Summary of key findings
└── README.md
```

---

## How to Run

```bash
git clone https://github.com/Tavishi-Jain/EDA_zomato-DataSet.git
cd EDA_zomato-DataSet
pip install pandas matplotlib seaborn jupyter
jupyter notebook "EDA on zomato dataset.ipynb"
```

---

## Author

**Tavishi Jain** — B.Tech CSE & Applied Mathematics  
