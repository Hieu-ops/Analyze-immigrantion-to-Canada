# 📊 Canada Immigration Data Analysis (1980–2013)

In this project, i analyze Canada's immigration data from 1980 to 2013 to uncover trends, patterns, and insights using pandas and matplotlib.

---

## 🧹 1. Data Cleaning

We begin by cleaning our dataset. Key tasks include:

- Renaming column headers for readability.
- Converting year columns to string or numeric format.
- Filtering the data to focus on specific countries, regions, or development classifications (e.g., top 5 countries by immigration).
- Resetting indexes and transposing data to support time-series analysis and visualization.
---

## 🔍 2. Data Exploration

Once the data is cleaned, we explore several key questions to better understand historical immigration trends:

- Which five countries contributed the most immigrants overall?
- How has the total number of immigrants changed over the years?
- Which regions had the highest total immigration to Canada?
- What is the immigration pattern by development status?
- Which country experienced the highest growth or decline in immigration?

To answer these questions, we use various data analysis and visualization techniques including:

- **GroupBy** operations to summarize data by region and development group.
- **Transpose and slicing** to reformat time-series data.
- **Sorting and filtering** to identify top countries.
- **Applying** custom functions to transform data.

---

## 📈 3. Visualization

We used `matplotlib` and `pandas` built-in plotting to create the following visuals:

- **Line plots** showing immigration trends over time.
- **Area charts** to compare top countries.
- **Bar charts (horizontal and vertical)** to show aggregated totals by region or development status.
- **Annotating charts** to enhance readability.

All graphs are labeled clearly with axis titles and legends for better interpretation.

---

## 🛠️ Tools Used

- Python
- pandas
- matplotlib

---

## 📁 Files

- `Immigrants_to_Canada.ipynb` – main Jupyter Notebook containing analysis and visualization code.
- `Canada.csv` – source dataset containing immigration data from 1980 to 2013.

---

## ✅ Summary

This project is a great introduction to working with time-series data using pandas and matplotlib. It demonstrates how to explore and visualize real-world data to support insights and decision-making.

