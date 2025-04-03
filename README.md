GDP Analysis from Wikipedia
This repository contains a Python script designed to extract and analyze GDP data from Wikipedia. It fetches GDP data for various countries, cleans and processes it, performs basic analysis, and visualizes the results.

Project Overview
This project utilizes data from the Wikipedia page "List of countries by GDP (nominal)" to extract GDP estimates, along with the sources (IMF, World Bank, United Nations), and the years of the estimates. The script processes the data to convert GDP values from millions to billions of USD, performs basic statistical analysis, identifies the top 10 countries by GDP, and generates a bar chart for visual comparison.

Data Source
The GDP data is extracted from the following Wikipedia page:

List of countries by GDP (nominal)

Requirements
To run this project, you'll need Python 3.6 or higher and the following libraries:

requests - for making HTTP requests to fetch the webpage

beautifulsoup4 - for parsing and extracting data from HTML

pandas - for data manipulation and analysis

matplotlib - for visualizing the data

You can install the required libraries by running the following command:

bash
Copy
Edit
pip install requests beautifulsoup4 pandas matplotlib
Usage
Clone the repository:

First, clone this repository to your local machine:

bash
Copy
Edit
git clone [redacted link]
Run the script:

Navigate to the project directory and run the script:

bash
Copy
Edit
python gdp_analysis.py
Script Output:

The script will generate the following outputs:

Summary statistics for the GDP estimates.

A list of the top 10 countries by IMF GDP estimate.

A bar chart comparing the GDP of the top 10 countries.

A CSV file named gdp_data.csv containing the cleaned and processed GDP data.

Output
The script produces the following outputs:

CSV file (gdp_data.csv): Contains the extracted and cleaned GDP data.

Summary Statistics: Displays the basic statistical summary of the GDP estimates.

Top 10 Countries by GDP: Lists the top 10 countries based on the IMF GDP estimate.

Visualization: A bar chart comparing the GDP of the top 10 countries.

Example Output
After running the script, you'll see:

A printed summary of the GDP data.

A CSV file (gdp_data.csv) saved in the project directory.

A bar chart displayed showing the GDP of the top 10 countries.

Disclaimer
This project is intended for educational purposes. The data is sourced from Wikipedia and may not be fully accurate or up-to-date. Use the data with caution for any critical analysis.
