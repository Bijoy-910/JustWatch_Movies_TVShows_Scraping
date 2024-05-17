![JustWatch_Pic](https://github.com/Bijoy-910/JustWatch_Movies_TVShows_Scraping/assets/52617079/e2d31719-d830-4523-bc20-b267faa9fbde)

# JustWatch Movies and TV Shows Scraping

This project involves web scraping of movie and TV show data from the JustWatch website using Python and BeautifulSoup. 
JustWatch is a popular platform that allows users to search for movies and TV shows across various streaming services like Netflix, Amazon Prime, Hulu, etc.

## Overview

The project is divided into several stages:

1. **Web Scraping**: Utilizing BeautifulSoup and requests libraries in Python to extract information about movies and TV shows from the JustWatch website. This includes details such as title, release year, genre, IMDb rating, runtime, age rating, production country, streaming service providers, and URLs.

2. **Data Filtering & Analysis**: After scraping the data, Pandas library is used to filter and analyze the dataset. This involves filtering movies and TV shows based on specific criteria like release year and IMDb rating, calculating average IMDb ratings, identifying top genres, and determining the streaming service with the most offerings.

3. **Data Export**: The filtered and analyzed data is then exported into a CSV file for further processing and reporting.

## Project Structure

- `justwatch_scraping.ipynb`: Jupyter Notebook containing the Python code for web scraping movies and TV shows from the JustWatch website.
- `JustWatch Final Data.csv`: CSV file containing the final combined dataset of movies and TV shows after filtering and analysis.
- `README.md`: This file providing an overview of the project and instructions for usage.

## Requirements

- Python 3.x
- BeautifulSoup4
- requests
- Pandas
- Matplotlib (for visualization)
- Wordcloud (for visualization)
