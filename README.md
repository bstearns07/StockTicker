# 📈 Stock Ticker

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![Data](https://img.shields.io/badge/Data-Finance-green?style=flat-square)
![Visualization](https://img.shields.io/badge/Visualization-Matplotlib-orange?style=flat-square)
![API](https://img.shields.io/badge/API-yFinance-lightgrey?style=flat-square)

---

## 👤 Author
Ben Stearns - [@bstearns07](https://github.com/bstearns07)

📅 Last Updated: 10-1-25

---
## 📑 Table of Contents
- 📌 [Summary](#-summary)
- ⭐ [How It Works](#-how-it-works)
- ✨ [Features](#-features)
- 🧰 [Tech Stack](#-tech-stack)
- 🔧 [Development Tools](#-development-tools)
- 🧩 [Core Concepts](#-core-concepts)
- 📝 [New Topics Covered](#-new-topics-covered)
- 📘 [What I Learned](#-what-i-learned)
- 🖼 [Screenshots](#-screenshots)

---

## 📌 Summary

The **Stock Ticker** application is a Python-based command-line tool that allows users to retrieve and visualize stock market data for one or more ticker symbols.

Users can input multiple stock tickers and select a time range to:
- View recent stock data
- Analyze trends
- Visualize closing prices through a line chart

This project demonstrates real-world API usage and data visualization techniques.

---

## ⭐ How It Works

1. Run the program in a Python environment
2. Enter one or more stock ticker symbols (e.g., `AAPL MSFT TSLA`)
3. Choose a time period (e.g., `1mo`, `6mo`, `1y`)
4. The program will:
   - Retrieve stock data using the yFinance API
   - Display the first 5 rows of results
   - Generate a line chart of closing prices

---

## ✨ Features

- 📊 Retrieve real-time stock data using yFinance
- 📅 Flexible time period selection with validation
- 🔍 Supports multiple ticker symbols at once
- 📈 Dynamic line chart visualization
- ⚠️ Error handling for invalid tickers or missing data
- 🔇 Clean output by suppressing unnecessary logging

---

## 🧰 Tech Stack

- 🐍 Python
- 📡 yFinance API
- 📊 Matplotlib
- 🧮 Pandas (via yFinance)

---

## 🔧 Development Tools

- 💻 VS Code / Python IDE
- 🐍 Python 3.x
- 📦 pip (package management)

---

## 🧩 Core Concepts

- API data retrieval
- Data manipulation with Pandas
- Data visualization with Matplotlib
- Input validation and error handling
- Looping and conditional logic

---

## 📝 New Topics Covered

- Using third-party APIs (`yfinance`)
- Working with financial datasets
- Handling missing or invalid data gracefully
- Plotting multi-line charts dynamically
- Logging control for cleaner console output

---

## 📘 What I Learned

This project helped reinforce several important development concepts:

- How to integrate external APIs into Python applications
- The importance of validating user input
- Techniques for visualizing data in a meaningful way
- Handling edge cases such as invalid ticker symbols or empty datasets
- Writing cleaner console applications with user-friendly output

---

## 🖼 Screenshots

> 📌 *Add screenshots here to showcase:*
- Console input/output
- Sample stock data table
- Generated line chart

Example:
```md
![Sample Output](images/sample-output.png)
![Chart](images/chart.png)
