# COVID-19 Global Trends & Analysis
### *An Interactive Visualization Suite using Plotly Express*

## 📖 Project Overview
This project provides a deep-dive analysis of the COVID-19 pandemic using Python. It focuses on transforming static datasets into **dynamic, interactive storytelling tools**. By utilizing **Plotly Express**, the project visualizes the global spread, identifies mortality correlations, and tracks recovery trends across different continents and specific regions like the US.

The workflow covers the entire data science pipeline:
1.  **Data Acquisition:** Loading multiple pandemic-related datasets.
2.  **Data Cleaning:** Handling missing values and dropping redundant columns (e.g., `NewCases`, `NewDeaths`).
3.  **Exploratory Data Analysis (EDA):** Aggregating stats by continent and WHO region.
4.  **Advanced Visualization:** Implementing animated maps and word clouds for qualitative insights.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Environment:** Jupyter Notebook / Google Colab
* **Libraries:**
    * `Pandas`: For high-performance data manipulation.
    * `Plotly Express & Graph Objects`: For interactive and animated charting.
    * `Matplotlib`: For secondary static plotting.
    * `WordCloud`: For text-based analysis of underlying health conditions.

---

## 📂 Repository Structure
* `Covid-19 Analysis and Visualization using Plotly Express.ipynb`: The main execution notebook.
* `covid.csv`: Global snapshot of total cases, deaths, and tests.
* `covid_grouped.csv`: Time-series data for daily progression analysis.
* `coviddeath.csv`: Specialized dataset focused on health conditions/comorbidities.

---

## 📊 Detailed Analysis Breakdown

### 1. Global Metrics & Comparisons
Using interactive Bar and Scatter charts, the project compares:
* **Total Cases vs. Total Deaths:** Understanding the severity of the virus per country.
* **Testing Capacity:** Visualizing `Tests/1M pop` to see how testing volume correlates with detected cases.
* **Continent-wise Distribution:** Grouping data to find which global regions faced the highest impact.

### 2. Temporal Analysis (Time-Series)
Focusing on the progression over time:
* **Daily Growth:** Tracking the rise of confirmed cases and fatalities from the start of the pandemic.
* **US Specific Deep-Dive:** A dedicated section analyzing the trend of new cases vs. recoveries specifically within the United States.

### 3. Geospatial Intelligence
The project uses **Choropleth Maps** with `animation_frame="Date"`. This allows users to press "Play" and watch the virus spread across the globe geographically from day one to the peak of the pandemic.

### 4. Qualitative Mortality Analysis
Beyond numbers, the project analyzes the *why*. 
* **Word Clouds:** Generated from the `Condition` column to highlight the most common health issues (like respiratory failure or pneumonia) mentioned in COVID-19 death records.

---

## 🚀 How to Run
1. **Clone the repo:**
   ```bash
   git clone https://github.com/yourusername/covid-analysis-plotly.git
   ```
2. **Install requirements:**
   ```bash
   pip install pandas plotly matplotlib wordcloud
   ```
3. **Execution:**
   Ensure the three `.csv` files are in the same directory as the notebook. Open the notebook and run all cells to generate the interactive widgets.

---

## 💡 Key Insights from the Data
* **Testing vs. Detection:** Countries with higher testing per million people showed a direct correlation with higher reported confirmed cases.
* **Regional Dominance:** The WHO region analysis highlights how different parts of the world hit their "peaks" at different time intervals.
* **Comorbidities:** The word cloud reveals a high frequency of specific respiratory and chronic conditions associated with critical cases.

---

## 👤 Author
**Tanuj Kumar** *Artificial Intelligence and Data Science Student*
