# Mars News and Weather Data Analysis

## Overview

This project demonstrates web scraping and data analysis skills by extracting and analyzing data related to Mars. The assignment is divided into two parts:

1. **Mars News Scraper**: Scrapes titles and preview text of the latest news articles from the Mars News website.
2. **Mars Weather Analysis**: Scrapes, cleans, and analyzes weather data from the Mars Temperature Data site to gain insights into Martian weather patterns.

## Deliverables

### Deliverable 1: Mars News Scraper
- Utilized **Splinter** for automated browsing and **Beautiful Soup** for HTML parsing.
- Extracted news titles and preview text from the [Mars News website](https://redplanetscience.com).

### Deliverable 2: Mars Weather Analysis
Used Splinter and Beautiful Soup to scrape weather data from the Mars Temperature Data Site.
Parsed the HTML table and converted it into a Pandas DataFrame with the following columns:
- id, terrestrial_date, sol, ls, month, min_temp, pressure.

Performed data analysis to answer the following questions:
1. How many months exist on Mars?
2. How many Martian days' worth of data exist in the dataset?
3. What are the coldest and warmest months on Mars (average minimum temperature)?
4. Which months have the lowest and highest atmospheric pressure?
5. How many terrestrial days exist in a Martian year?

Visualized results using bar charts and plotted daily minimum temperatures to estimate a Martian year.
Exported the final DataFrame to a CSV file.

### Technologies Used
- Python: Core programming language.
- Splinter: Automated browser navigation.
- Beautiful Soup: HTML parsing for data extraction.
- Pandas: Data manipulation and analysis.
- Matplotlib: Data visualization.
