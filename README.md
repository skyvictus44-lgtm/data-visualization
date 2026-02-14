# data-visualization

---

#  Customer Purchase Behavior Analysis & Data Visualization

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-lightblue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Status](https://img.shields.io/badge/Project-Showcase%20Ready-brightgreen.svg)

---

##  Project Summary

This project demonstrates **end-to-end exploratory data analysis (EDA) and data visualization** on customer transaction data.

The focus is on **transforming raw data into meaningful visual insights** by applying data preprocessing, feature engineering, and analytical plotting techniques. The project reflects practical skills expected from an **entry-level Data Analyst / Data Scientist**.

---

##  Key Goals

* Perform structured data cleaning and preprocessing
* Engineer time-based customer features (recency, frequency)
* Apply exploratory data analysis to uncover trends
* Design clear, professional, and insight-driven visualizations
* Present findings in a GitHub-ready, reproducible format

---

##  Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning & Feature Engineering
* Time-Series Analysis
* Statistical Visualization
* Insight Communication
* Reproducible Notebook Design

---

##  Tech Stack

| Category      | Tools               |
| ------------- | ------------------- |
| Language      | Python              |
| Data Handling | Pandas              |
| Visualization | Matplotlib, Seaborn |
| Environment   | Jupyter Notebook    |

---

##  Dataset Overview

The dataset contains customer purchase records with fields related to:

* Customer identification
* Purchase timestamps
* Purchase frequency
* Transaction behavior

Date fields are converted to `datetime` format to support **time-based analysis** and recency calculations.

---

##  Data Preparation & Feature Engineering

Key preprocessing steps:

* Handling missing and inconsistent values
* Datetime conversion for temporal analysis
* Creation of derived features:

  * **Recency** – days since last purchase
  * **Frequency** – number of purchases per customer
* Aggregation at customer level for behavioral insights

This ensures the dataset is **analysis-ready and reliable**.

---

##  Exploratory Data Analysis & Visualizations

###  Purchase Frequency Distribution

Analyzes how often customers make purchases, highlighting heavy vs light buyers.

 **Visualization:**
![Purchase Frequency](screenshots/purchase_frequency.png)

---

###  Customer Activity Over Time

Time-series visualization showing trends and fluctuations in customer purchases.

 **Visualization:**
![Customer Activity Over Time](screenshots/activity_over_time.png)

---

###  Recency Analysis

Visualizes how recently customers have interacted, useful for identifying inactive customers.

 **Visualization:**
![Recency Analysis](screenshots/recency_analysis.png)

---

###  Comparative & Distribution Analysis

Additional plots to compare multiple customer metrics and uncover hidden patterns.

 **Visualization:**
![Additional Plots](screenshots/additional_plots.png)


---

##  Insights & Observations

* A small subset of customers shows high purchase frequency
* Customer engagement varies significantly over time
* Recency analysis helps identify churn-risk customers
* Visual exploration simplifies complex behavioral patterns

---

##  Repository Structure

```
Customer-Purchase-EDA/
│
├── DV_Project_2.ipynb        # Main analysis notebook
├── README.md                # Project documentation
├── data/                    # Dataset (optional)
└── screenshots/             # Saved visualizations
```

---

##  How to Run

```bash
git clone https://github.com/your-username/Customer-Purchase-EDA.git
pip install pandas matplotlib seaborn
jupyter notebook DV_Project_2.ipynb
```

---

##  Future Enhancements

* Interactive dashboards using **Plotly / Dash**
* **RFM segmentation** for advanced customer analysis
* Integration with SQL-based datasets
* Automated reporting pipelines


---

##  Why This Project Matters

This project reflects:

* Real-world data handling
* Strong visualization fundamentals
* Clear analytical thinking
* Professional documentation


