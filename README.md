# Tesla & GameStop Stock and Revenue Analysis

Comparative analysis of historical stock prices and revenues for Tesla and GameStop. Built with Python using yfinance for market data, web scraping (BeautifulSoup) for financial records, and Pandas for data cleaning, integration, and visualization.

## Project Objective
Extracting essential data from a dataset and displaying it is a necessary part of data science to make informed decisions. This project demonstrates the ability to programmatically collect financial data from different sources, clean it, and visualize it in a comparative static dashboard (Share Price vs. Revenue).

## Technologies & Tools Used
* **Language:** Python
* **Data Manipulation:** Pandas
* **Web Scraping:** BeautifulSoup (`bs4`), Requests
* **Financial Data API:** `yfinance`
* **Data Visualization:** Matplotlib
* **Environment:** Jupyter Notebook / Google Colab

##  Methodology & Steps
1. **API Data Extraction:** Used the `yfinance` library to retrieve historical stock price data for Tesla (TSLA) and GameStop (GME) up to the maximum available period.
2. **Web Scraping:** Utilized `requests` and `BeautifulSoup` to parse HTML data and extract quarterly revenue tables from external websites.
3. **Data Cleaning:** Processed the scraped data with `pandas` by removing special characters (like `$` and `,`), handling empty strings, and dropping missing values (`NaN`).
4. **Data Visualization:** Plotted the historical share prices against historical revenues up to mid-2021 using `matplotlib` to create an analytical dashboard.

##  Acknowledgments
This project was developed as part of the Python for Data Science, AI & Development course / IBM Data Science Professional Certificate on Coursera.
