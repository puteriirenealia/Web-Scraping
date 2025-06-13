# Web Scraping Project: Stock and Revenue Data Analysis

This project, part of the IBM Python Project for Data Science, focuses on demonstrating practical web scraping techniques and data analysis using Python. It involves extracting financial data (stock prices and revenue) from various online sources and visualizing it.

## Project Overview

The primary goal of this project is to illustrate end-to-end data acquisition from web sources (financial APIs and direct web scraping), data processing, and basic visualization. It covers essential libraries for web interaction, HTML parsing, and data manipulation.

## Key Features & Learning Outcomes

This project addresses several core data science tasks through a series of questions and exercises:

### 1. Stock Data Extraction with `yfinance`

* **Question 1 & 3: Use `yfinance` to Extract Stock Data**
    * Demonstrates how to fetch historical stock information for specific companies (e.g., Tesla, GameStop) using the `yfinance` library.
* **Extracting Historical Share Price Data**
    * Utilizes `yfinance` to obtain detailed historical share price data, including open, high, low, close, and volume.
* **Extracting Historical Dividends Data**
    * Shows how to retrieve historical dividend payout information for a given stock.

### 2. Web Scraping Revenue Data with `BeautifulSoup`

* **Question 2 & 4: Use Webscraping to Extract Tesla/GME Revenue Data**
    * Focuses on extracting financial revenue data from web pages.
* **Downloading the Web Page Using Requests Library**
    * Explains how to make HTTP requests to download HTML content from a given URL.
* **Parse HTML on a Web Page using BeautifulSoup**
    * Covers the fundamentals of parsing raw HTML into a searchable `BeautifulSoup` object.
* **Extract Data and Build a DataFrame**
    * Demonstrates how to navigate the parsed HTML tree to locate specific data points and then structure them into a `pandas` DataFrame.
* **BeautifulSoup Concepts Explored:**
    * Understanding the `BeautifulSoup` Object, Tags, Children, Parents, and Siblings.
    * Working with HTML Attributes and Navigable Strings.
    * Applying Filters, `find_all()`, and `find()` methods for efficient data extraction.
* **Downloading and Scraping the Contents of a Web**
    * A comprehensive approach to fetching and parsing web content for data.

### 3. Data Extraction with `pandas`

* **Extracting data using `pandas`**
    * Explores methods within the `pandas` library for reading data, potentially directly from HTML tables or structured formats, and performing initial data cleaning.

### 4. Data Visualization

* **Question 5: Plot Tesla Stock Graph**
* **Question 6: Plot GameStop Stock Graph**
    * Illustrates how to create time-series plots of historical stock data, likely using `matplotlib` or `seaborn`, to visualize trends and patterns.

## Technologies Used

* Python
* `yfinance` (for stock data)
* `requests` (for HTTP requests)
* `BeautifulSoup` (for HTML parsing and web scraping)
* `pandas` (for data manipulation and DataFrame creation)
* `matplotlib` (for plotting/graphing)
* `seaborn` (for enhanced visualizations)
