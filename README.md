# README: Web Scraping, Data Cleaning, and Visualization

## Project Title
**Book Data Scraper and Analyzer**

## Description
This project provides a complete end-to-end solution for web scraping product information from an e-commerce site, cleaning the extracted data, and performing basic visualizations to gain insights. It specifically targets `books.toscrape.com` to demonstrate the process of fetching book titles, prices, and ratings, transforming this raw data into a structured format, and presenting it visually.

## Features
- **Web Scraping**: Efficiently extracts book titles, prices, and star ratings from `books.toscrape.com`.
- **Data Structuring**: Organizes scraped data into a `pandas.DataFrame` for easy manipulation.
- **Data Cleaning**: Converts string-based prices (e.g., 'Â£51.77') into numerical floats and text ratings (e.g., 'One', 'Two') into integer star counts (1, 2).
- **Data Visualization**: Generates insightful plots to understand:
    - The distribution of book prices.
    - The distribution of star ratings among the books.

## Technologies Used
- **Python**: The core programming language.
- **`requests`**: For making HTTP requests to fetch webpage content.
- **`BeautifulSoup4` (`bs4`)**: For parsing HTML and XML documents.
- **`pandas`**: A powerful library for data manipulation and analysis.
- **`re`**: Python's built-in regular expression module for string processing.
- **`matplotlib.pyplot`**: For creating static, interactive, and animated visualizations.
- **`seaborn`**: A high-level data visualization library based on `matplotlib`.

## Getting Started

### Prerequisites
Ensure you have Python installed. The project uses several standard Python libraries that can be installed via `pip`.

### Installation
1.  **Clone the repository** (if applicable) or download the script.
2.  **Install the required libraries** using `pip`:
    ```bash
    pip install requests beautifulsoup4 pandas matplotlib seaborn
    ```

### Usage
1.  **Run the Python script** (e.g., in a Jupyter Notebook, Google Colab, or from your terminal):
    ```bash
    python your_script_name.py
    ```
2.  The script will:
    - Fetch data from `https://books.toscrape.com/`.
    - Print the head of the cleaned `pandas.DataFrame`.
    - Display two plots: a histogram of book prices and a bar chart of book ratings.

### Example Output
- A `pandas.DataFrame` showing 'Title', original 'Price', original 'Rating', and the new 'Price_Float' and 'Rating_Num' columns.
- Two graphical plots illustrating price and rating distributions.

This project is ideal for learning about fundamental web scraping, data cleaning, and visualization techniques in Python.
