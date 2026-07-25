# 📈 Stock Market Analysis Tool

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)

## 🚀 Overview
The **Stock Market Analysis Tool** is a comprehensive, interactive Python program built to run within a Jupyter Notebook environment. It provides a powerful command-line style interface to perform data cleaning, exploratory data analysis (EDA), and advanced financial metrics calculations on stock market datasets. 

## ✨ Features
This tool is powered by `pandas`, `numpy`, `matplotlib.pyplot`, and `seaborn`. It features a robust 10-step menu-driven system tailored for financial data:

* **Data Loading & Exploration:** Seamlessly load datasets from CSV, Excel, or JSON files. Explore your data by viewing top/bottom rows, column names, data types, and generating a full statistical summary. It automatically processes essential stock attributes including `symbol`, `date`, `open`, `high`, `low`, `close`, and `volume`.
* **Data Cleaning Strategies:** View missing values summaries and handle them efficiently by filling with mean values, dropping empty rows, or replacing them with specific custom values. It also includes a dedicated duplicate rows removal function.
* **Advanced Market Analysis:** Perform moving average analysis and determine overall market trends (e.g., identifying a "DOWNTREND" based on SMA vs. Latest Price). 
* **Volatility & Returns:** Calculate daily returns and perform deep volatility analysis to assess specific market conditions (e.g., classifying data as "LOW / NORMAL VOLATILITY (Stable)").
* **Pattern Discovery:** Utilize built-in data visualization techniques to find underlying patterns in the financial dataset.
* **Dataset Export:** Export the fully cleaned and processed dataset for future modeling or record-keeping.

## 💻 Usage
To utilize this tool, open the notebook in your preferred environment (such as Jupyter Notebook or VS Code) and run the cell to launch the interactive main menu:
```bash
jupyter notebook Stock_market_analysis.ipynb