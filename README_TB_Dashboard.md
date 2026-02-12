# 🏥 Tuberculosis Data Dashboard

## 📊 Overview
This interactive dashboard provides a comprehensive analysis of global **Tuberculosis (TB)** trends from **1990 to 2013**, with additional predictive modeling and comparisons to **2024 data**. Built with Python and integrated into a Jupyter Notebook, it allows researchers and policymakers to explore the burden of TB across different countries and **WHO regions**.

The dashboard includes dynamic filtering, predictive analytics using **Linear Regression**, and comparative studies between historical averages and modern data.

---

## 🚀 Features

### 🎛️ Interactive Controls
- **Year Slider**: Analyze data dynamically for any year between **1990 and 2013**.
- **Region Selector**: Filter data by **WHO Region** (e.g., Africa, Americas, Europe, South-East Asia).

### 📈 Key Performance Indicators (KPIs)
- **Total TB Cases**: Aggregated count based on active filters.
- **Average Incidence Rate**: Cases per 100,000 population.

### 🎨 Visualizations
1.  **Global Trend Analysis**:
    -   Interactive **Line Chart** showing global TB cases over time.
    -   **Linear Regression Prediction**: Visualizes historical trends (1990-2013) and projects future cases for 2014, 2015, and 2020.
2.  **Country-Level Breakdown**:
    -   **Bar Chart** highlighting the **Top 10 Countries** by total TB cases for the selected year.
    -   Features a 'Turbo' color scale for better visibility of high-burden areas.
3.  **Regional Distribution**:
    -   **Donut Chart** displaying the market share of TB cases across WHO regions.
4.  **Historical vs. Present Day Analysis**:
    -   **Grouped Bar Chart** comparing **Historical Averages (1990–2013)** against **2024 TB Case estimates**.
    -   Calculates and displays percentage changes for high-burden nations like India, Nigeria, and China.

---

## 🛠️ Technologies & Libraries Used
-   **Python**: Core programming language.
-   **Pandas & NumPy**: Data manipulation and analysis.
-   **Plotly (Express & Graph Objects)**: Interactive and publication-quality graphing.
-   **IPyWidgets**: UI controls for interactivity (Sliders, Dropdowns).
-   **Scikit-Learn**: Machine learning for trend prediction (Linear Regression).

---

## 📂 Data Sources
The dashboard processes data from the following CSV files:
1.  `TB_Burden_Country.csv`: Detailed historical records (1990–2013) including country, region, year, population, and incidence rates.
2.  `Tuberculosis_Trends.csv`: Recent dataset used for the 2024 comparison analysis.

---

## ⚙️ Setup Instructions

1.  **Prerequisites**: Ensure you have Python installed along with Jupyter Notebook or JupyterLab.
2.  **Install Dependencies**:
    ```bash
    pip install pandas numpy plotly ipywidgets scikit-learn
    ```
3.  **Run the Dashboard**:
    -   Open `Tuberculosis_Data_Dashboard.ipynb` in Jupyter.
    -   Run all cells to load data and initialize the interactive dashboard.
    -   Use the slider and dropdowns to interact with the visualizations.

---

## 🔍 Key Insights
-   **Historical Peak**: Global TB cases saw a peak in the early 2000s before stabilizing.
-   **Regional Burden**: The **African (AFR)** and **South-East Asian (SEA)** regions consistently bear the highest TB burden.
-   **Future Outlook**: Simple linear regression models suggest a potential decline, provided global health interventions continue.
-   **2024 Comparison**: The comparison chart highlights which countries have managed to reduce their average caseload versus those seeing an increase.
