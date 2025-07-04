# stock-analysis

# 📊 Tesla and GameStop Stock & Revenue Dashboard

This repository contains my final assignment for the **IBM Data Science Professional Certificate**.  
The project analyzes the **historical stock performance and quarterly revenues** of **Tesla (TSLA)** and **GameStop (GME)** using:

- 🟦 `yfinance` for stock data
- 🌐 Web scraping with `pandas.read_html()` for revenue data from Macrotrends
- 📈 Interactive visualizations using `Plotly`

---

## 🚀 Project Overview

The goal of this project is to demonstrate key data science skills, including:

- Data extraction from APIs and websites
- Data cleaning and preprocessing
- Exploratory data analysis and visualization

The project follows a question-based structure:

| Question | Description |
|----------|-------------|
| Q1       | Extract Tesla stock data using `yfinance` |
| Q2       | Extract Tesla revenue data using web scraping |
| Q3       | Extract GameStop stock data using `yfinance` |
| Q4       | Extract GameStop revenue data using web scraping |
| Q5       | Build a dashboard to visualize Tesla stock price vs revenue |
| Q6       | Build a dashboard to visualize GameStop stock price vs revenue |
| Q7       | Save and share the notebook output |

---

## 📂 Files in This Repository

- `Final_Assignment.ipynb` — Jupyter notebook with all code and visualizations
- `README.md` — You’re reading it!
- `images/` — Optional folder for screenshots (for submission or GitHub preview)

---

## 📊 Visuals

The project uses Plotly to generate **interactive line graphs** for each company:

- Stock prices over time (from Yahoo Finance)
- Quarterly revenue (scraped from Macrotrends)
- Combined dashboards with dual Y-axes

---

## 📦 Libraries Used

- `pandas`
- `yfinance`
- `requests` *(for earlier attempts at scraping)*
- `plotly`
- `BeautifulSoup` *(optional)*
- `lxml` *(for HTML parsing)*

Install dependencies using:

```bash
pip install pandas yfinance plotly beautifulsoup4 lxml
