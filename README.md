# IMDb Top 250 Movies Web Scraping

This Python project extracts and analyzes the IMDb Top 250 movies list from the IMDb website. Using web scraping techniques, it collects key information about the movies, including their rank, title, release year and IMDb rating.

## Project Overview

The purpose of this project is to retrieve IMDb's Top 250 movies list by scraping data from the IMDb Charts webpage. The project uses the following steps:
1. **HTTP Requests**: Sending a request to the IMDb webpage.
2. **HTML Parsing**: Parsing the page using BeautifulSoup to extract the movie data.
3. **Data Storage**: Saving the data in structured formats (CSV/JSON).
4. **Error Handling**: Managing potential access issues (e.g., 403 Forbidden errors) by using headers to mimic a real browser.

## Technologies Used
- Python 
- `requests`: To send HTTP requests to the IMDb website.
- `BeautifulSoup`: To parse HTML content and extract relevant movie data.
- `csv`: For storing the extracted data in structured formats.
## Features
- Scraping IMDb Top 250 movies data using Python
- Display movie details such as title, year, genre, director, actors, and rating
- Ability to filter movies by year, rating, or genre
- Export the data to a CSV or Excel file for offline use
  
## Installation Instructions

Install the required Python libraries:
   pip install requests beautifulsoup4
  
