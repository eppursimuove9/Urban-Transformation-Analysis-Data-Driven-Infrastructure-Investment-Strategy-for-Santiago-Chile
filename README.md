# Urban-Transformation-Analysis-Data-Driven-Infrastructure-Investment-Strategy-for-Santiago-Chile

# Santiago 2035: A Data-Driven Urban Transformation Analysis

![Project Status](https://img.shields.io/badge/status-complete-green)
![Python Version](https://img.shields.io/badge/python-3.9+-blue)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

### Project Overview

This repository contains a comprehensive data analysis and financial model for a proposed $50 billion, 10-year transformation plan for Santiago, Chile. The project leverages public data from the Oxford Economics Global Cities Index to diagnose Santiago's primary weaknesses—particularly in its environmental score—and models the economic and social returns of targeted green infrastructure investments.

The analysis projects a potential **$103.1 billion in total benefits** from a **$14.3 billion investment**, resulting in a **Net Present Value (NPV) of $52.7 billion** and a **Benefit-Cost Ratio of 7.2:1**. The goal is to provide a data-backed roadmap for elevating Santiago from its current global rank of #160 into the top 100 cities worldwide by 2035.

---

### Skills & Technologies Demonstrated

* **Data Analysis:** Python (Pandas, NumPy) for data manipulation and statistical analysis.
* **Predictive Modeling:** Time-series analysis (ARIMA concepts) for environmental projections and exponential regression for financial returns.
* **Financial Modeling:** ROI calculation, Net Present Value (NPV), and Benefit-Cost Ratio analysis.
* **Risk Assessment:** Monte Carlo simulation concepts for evaluating project viability under uncertainty.
* **Data Visualization:** Plotly for creating interactive and insightful charts (Radar, Treemap, Waterfall, Sankey, etc.).
* **Project Structuring:** Professional Git repository structure, clear documentation, and reproducible code.

---

### Key Visualizations

<table>
  <tr>
    <td><strong>Santiago Performance Matrix (2025)</strong></td>
    <td><strong>Projected Return on Investment (2025-2035)</strong></td>
  </tr>
  <tr>
    <td><img src="reports/images/performance_matrix.png" alt="Performance Matrix Radar Chart" width="400"></td>
    <td><img src="reports/images/roi_timeline.png" alt="ROI Timeline Area Chart" width="400"></td>
  </tr>
</table>

---

### Repository Structure

```
santiago-2035-analysis/
│
├── .gitignore          # Specifies files for Git to ignore
├── LICENSE             # Project license
├── README.md           # This overview file
├── requirements.txt    # Python package dependencies
│
├── data/
│   ├── raw/            # Original, untouched data sources
│   └── processed/      # Cleaned and processed data
│
├── notebooks/          # Jupyter notebooks for analysis steps
│   ├── 01_Data_Exploration_and_Benchmarking.ipynb
│   ├── 02_Financial_and_Environmental_Modeling.ipynb
│   └── 03_Dashboard_and_Final_Visualizations.ipynb
│
└── reports/
    └── images/         # Static images for README and reports
```

---

### Getting Started

To run this analysis on your local machine, follow these steps:

**1. Clone the repository:**
```bash
git clone [https://github.com/](https://github.com/)[YourUsername]/santiago-2035-analysis.git
cd santiago-2035-analysis
```

**2. Create and activate a virtual environment:**
```bash
# For Mac/Linux
python3 -m venv venv
source venv/bin/activate

# For Windows
python -m venv venv
.\venv\Scripts\activate
```

**3. Install the required packages:**
```bash
pip install -r requirements.txt
```

**4. Launch Jupyter Lab:**
```bash
jupyter lab
```
Now you can open and run the notebooks located in the `notebooks/` directory.

---

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
