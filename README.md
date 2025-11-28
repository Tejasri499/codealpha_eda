# Quotes Web Scraping & Exploratory Data Analysis (EDA)

## Project Overview
This project scrapes quotes from [Quotes to Scrape](http://quotes.toscrape.com/) and performs exploratory data analysis (EDA) to gain insights about authors, tags, and quote content. The final output includes a CSV dataset and multiple visualizations.

---

## Features
- Scrape quotes, authors, and tags from the website.
- Clean and preprocess the data for analysis.
- Generate visualizations:
  - Top authors by quote count
  - Most common tags
  - Word cloud of all quotes
  - Distribution of quote lengths
  - Distribution of tags per quote
- Save the dataset as `quotes_custom_dataset.csv`.

---

## Technologies & Libraries
- Python
- `requests` – to send HTTP requests
- `BeautifulSoup` – for HTML parsing
- `pandas` – for data manipulation
- `matplotlib` & `seaborn` – for data visualization
- `wordcloud` – for generating word clouds

---

## Installation
1. Clone the repository:
```bash
git clone <repository_url>
cd <repository_folder>
