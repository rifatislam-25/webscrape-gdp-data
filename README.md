# GDP Analysis

This repository contains a Python script designed to extract and analyze GDP data from Wikipedia. The script fetches GDP data for various countries, cleans and processes it, performs basic analysis, and visualizes the results.

## 📊 Project Overview

This project utilizes data from the Wikipedia page "List of countries by GDP (nominal)" to extract GDP estimates, along with their sources (IMF, World Bank, United Nations), and the years of the estimates. The script processes the data to:

- Convert GDP values from millions to billions of USD.
- Perform basic statistical analysis on GDP estimates.
- Identify the top 10 countries by GDP based on IMF estimates.
- Generate a bar chart for visual comparison of the top 10 countries' GDPs.

## 🔗 Data Source  
GDP data is extracted from the Wikipedia page:  
[List of countries by GDP (nominal)](https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal))

## 💻 Requirements  
To run this project, you'll need Python 3.6 or higher and the following libraries:

- **requests** – for making HTTP requests to fetch the webpage
- **beautifulsoup4** – for parsing and extracting data from HTML
- **pandas** – for data manipulation and analysis
- **matplotlib** – for visualizing the data

Install the required libraries using:

```bash
pip install requests beautifulsoup4 pandas matplotlib
