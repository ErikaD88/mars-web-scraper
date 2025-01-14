# mars-web-scraper

## Overview
This project involves web scraping and data analysis related to Mars. It includes two main tasks:
1. Scraping titles and preview text from Mars news articles.
2. Scraping and analyzing Mars weather data.

## Deliverables
### Deliverable 1: Scrape Titles and Preview Text from Mars News
- **Tools Used**: Splinter, BeautifulSoup, Python.
- **Tasks Completed**:
  - Automated browsing to visit the Mars news website.
  - Extracted titles and preview text for news articles.
  - Stored the data as a list of dictionaries with `title` and `preview` keys.
  - (Optional) Exported data to a JSON file.

### Deliverable 2: Scrape and Analyze Mars Weather Data
- **Tools Used**: Splinter, BeautifulSoup, Pandas, Matplotlib, Python.
- **Tasks Completed**:
  - Automated browsing to visit the Mars weather data website.
  - Extracted weather data from an HTML table into a Pandas DataFrame.
  - Cleaned and formatted the data, converting data types where necessary.
  - Analyzed the data to answer key questions:
    - How many months exist on Mars?
    - How many Martian days of data are available?
    - Which months have the lowest and highest average temperatures?
    - Which months have the lowest and highest average atmospheric pressure?
    - Estimated the number of terrestrial days in a Martian year.
  - Created visualizations:
    - Bar charts for average temperatures and atmospheric pressure by month.
    - A plot showing the daily minimum temperature trend to estimate the Martian year.
  - Exported the cleaned DataFrame to a CSV file.

## Files in the Repository
- `part_1_mars_news.ipynb`: Jupyter Notebook for scraping Mars news articles.
- `part_2_mars_weather.ipynb`: Jupyter Notebook for scraping and analyzing Mars weather data.
- `mars_weather.csv`: CSV file containing the cleaned Mars weather data.
- `README.md`: This file, describing the project.

## Requirements
- Python 3.x
- Libraries: Splinter, BeautifulSoup, Pandas, Matplotlib

## How to Run the Code
1. Install the required libraries.
2. Open each Jupyter Notebook (`.ipynb`) in a Jupyter environment.
3. Execute the cells sequentially to perform the tasks.
4. Review the outputs and visualizations in the notebooks.

## Acknowledgments
- The Mars news and weather data were sourced from static educational resources provided for this challenge
