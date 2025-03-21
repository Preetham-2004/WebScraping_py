# Cricket Stats Web Scraper

This Python project is a web scraping tool designed to fetch and visualize cricket player statistics using data from ESPN Cricinfo. It extracts batting and bowling data for various cricketers and plots their total runs over their career spans using Matplotlib.

## Features
- Scrapes player statistics using BeautifulSoup.
- Supports multiple player profiles using dynamic URL input.
- Cleans and organizes data using Pandas.
- Visualizes player performance using Matplotlib.

## Requirements
- Python 3.x
- BeautifulSoup4
- Requests
- Pandas
- NumPy
- Matplotlib
- IPython (for displaying dataframes)

You can install dependencies using:
```bash
pip install beautifulsoup4 requests pandas numpy matplotlib ipython
```

## How It Works
1. **Data Extraction**: The `get_cricket_stats()` function scrapes data from ESPN Cricinfo using BeautifulSoup.
2. **Data Cleaning**: Data is structured into dictionaries and then converted to Pandas DataFrames.
3. **Visualization**: The data is visualized using scatter plots to compare player performances over their career spans.

## Usage
1. Add the desired player URLs to the `links` list.
2. Update the `names` list with corresponding player names.
3. Run the script:
```bash
python cricket_stats_scraper.py
```
4. View the displayed dataframes and the performance plot.

## Example Output
- A dataframe showing player statistics like Runs, Average, Strike Rate, and more.
- A scatter plot visualizing total runs against the end of their career span.

## Notes
- Ensure the table structure on ESPN Cricinfo remains consistent for accurate scraping.
- Handle exceptions for invalid or changed URLs.

## License
This project is licensed under the MIT License.

---
*Built with Python, BeautifulSoup, and Matplotlib.*
