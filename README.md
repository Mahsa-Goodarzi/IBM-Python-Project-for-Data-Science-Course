# IBM Python Project for Data Science

This repository contains the final project for the [**Python Project for Data Science**](https://www.coursera.org/learn/python-project-for-data-science) course, provided by **IBM**  on **Coursera**. The project focuses on extracting essential financial data (stock prices and revenue) for Tesla and GameStop to build a dashboard for data visualization.

## Project Overview

The goal of this project is to demonstrate proficiency in Python for Data Science by extracting financial data from different sources, cleaning it, and visualizing trends over time.

The workflow includes:
1.  **Data Extraction via API:** Using the `yfinance` library to fetch historical stock data.
2.  **Web Scraping:** Using `BeautifulSoup` and `requests` to scrape quarterly revenue data from financial webpages.
3.  **Data Cleaning:** Processing raw HTML and DataFrames to handle formatting issues (removing symbols, handling null values).
4.  **Visualization:** Implementing a custom function (`make_graph`) to display stock prices and revenue trends on a dual-axis dashboard.

## Technologies & Libraries Used

The project utilizes the following Python libraries:

* **yfinance:** For retrieving stock market data.
* **BeautifulSoup (bs4):** For parsing HTML and web scraping.
* **Requests:** For making HTTP requests to web servers.
* **Pandas:** For data manipulation and DataFrame management.
* **Matplotlib:** For plotting and visualizing the data dashboards.

## Analysis Targets

The project analyzes data for two specific companies:
* **Tesla (TSLA)**
* **GameStop (GME)**
