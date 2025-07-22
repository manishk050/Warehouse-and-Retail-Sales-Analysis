# Montgomery County Sales Data Analysis

[![Project Status](https://img.shields.io/badge/Status-Completed-blue?style=for-the-badge)]()

This repository contains a complete data analysis project on the Montgomery County, MD "Warehouse and Retail Sales" dataset. The project walks through the entire data analysis workflow, from data cleaning and exploratory data analysis (EDA) in a Jupyter Notebook to the creation of a final, interactive single-page infographic that visualizes the key findings.

---

## 🚀 Project Overview

The goal of this project was to analyze historical sales data to uncover trends, identify key business drivers, and diagnose performance anomalies. The analysis tells a compelling story of a business dominated by a single product category, subject to extreme volatility, and marked by a critical, systemic sales collapse in 2018.

The final output is a responsive, single-page web infographic designed to present these complex findings in an easily digestible and engaging format.

---

## 📊 Key Findings & Visualizations

The analysis drilled down through four layers of inquiry to uncover the root cause of the business's performance issues.

### Finding 1: High-Level Volatility
The business's overall sales are extremely volatile, with no clear seasonal pattern. This pointed towards irregular, event-driven revenue rather than consistent consumer demand. The most significant anomaly is a major sales slump throughout 2018.

### Finding 2: The Dominance of a Single Category
A breakdown of revenue by item type revealed that the business is overwhelmingly dependent on alcoholic beverage sales. **Beer** is the undisputed leader, generating more than 3x the revenue of the next category, Wine.

### Finding 3: Beer Performance Dictates Business Health
Plotting the top categories over time confirmed that the overall sales volatility is almost exclusively a reflection of beer sales. The 2018 slump was, in fact, a "beer problem," as other categories remained relatively stable.

### Finding 4: The 2018 Mystery Solved - A Systemic Collapse
The final step was to investigate the cause of the 2018 beer slump. The analysis revealed it was not due to a single failed supplier relationship but a catastrophic, across-the-board sales collapse from **all major beer suppliers simultaneously**, with an average revenue drop of ~80%. This points to a systemic operational or policy failure, not a simple partner issue.

---

## 🛠️ Technology Stack

* **Data Analysis:**
    * **Python:** Core language for data manipulation.
    * **Pandas:** For data cleaning, transformation, and analysis.
    * **Matplotlib & Seaborn:** For generating initial static visualizations.
    * **Jupyter Notebook:** For interactive analysis and code development.
* **Frontend Infographic:**
    * **HTML5:** For the structure of the web page.
    * **Tailwind CSS:** For utility-first, responsive styling.
    * **Chart.js:** For creating responsive, interactive, canvas-based charts.

---

## 📂 Repository Structure

```
.
├── 📁 data/
│   └── Warehouse_and_Retail_Sales.csv   # The raw dataset
├── 📁 images/
│   └── (Screenshots of charts for README)
├── 📄 montgomery_county_analysis.ipynb   # Jupyter Notebook with the full Python analysis
├── 📄 index.html                         # The final single-page application infographic
└── 📄 README.md                          # You are here!
```

---

## ⚙️ Running the Project

### 1. Data Analysis
To explore the data analysis process:
* Ensure you have Python 3 installed.
* Install the required libraries:
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```
* Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
* Open the `montgomery_county_analysis.ipynb` file.

### 2. Infographic
To view the final infographic, simply open the `index.html` file in any modern web browser. No server is required.
---

