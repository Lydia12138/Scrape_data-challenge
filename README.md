# Mars News and Weather Analysis

## Introduction
This project is focused on web-scraping and data analysis of information related to Mars. The project consists of two parts: Part 1 is a Jupyter notebook containing code that scrapes the Mars news titles and preview text. Part 2 is a Jupyter notebook containing code that scrapes the Mars weather data and that cleans, visualizes, and analyzes that data.

#### Here are two main deliverables: 

Deliverable 1: Scrape titles and preview text from Mars news articles.
1. Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted.
2. The titles and preview text of the news articles were scraped and extracted.
3. The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
1. The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types.
2. The data was analyzed to answer the following questions: 

a. How many months exist on Mars?
b. How many Martian days' worth of data are there? 
c. Which month, on average, has the lowest temperature? The highest? 
d. Which month, on average, has the lowest atmospheric pressure? The highest? 
e. How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.

3. The DataFrame was exported into a CSV file.
[CSV with the data](https://github.com/Lydia12138/Scrape_data-challenge/blob/main/mars_weather.csv) 

## Data Source
1. [Mars News Website](https://static.bc-edx.com/data/web/mars_news/index.html)

2. [Mars Weather Facts Website](https://static.bc-edx.com/data/web/mars_facts/temperature.html)


