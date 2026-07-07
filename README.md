# Books to Scrape Web Scraper

## Overview

This project is a Python web scraper developed as part of my Codveda Data Science Internship. It extracts book information from the Books to Scrape website using web scraping techniques and stores the data in structured formats for further analysis.

## Features

- Scrapes all 50 pages (1,000 books)
- Extracts:
  - Book Title
  - Price
  - Rating
  - Availability
- Saves data as CSV
- Saves data as JSON
- Uses BeautifulSoup for HTML parsing
- Uses Requests for HTTP requests
- Uses Pandas for data processing

## Technologies Used

- Python
- Requests
- BeautifulSoup4
- Pandas

## Project Structure

```
Books-To-Scrape-Web-Scraper/
│
├── data/
│   ├── books.csv
│   └── books.json
│
├── notebooks/
│   └── Web_Scraping_Project.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation

```bash
pip install -r requirements.txt
```

## Run the Project

Open the Jupyter Notebook and execute the cells, or run the Python script if using the script version.

## Output

The scraper generates:

- `books.csv`
- `books.json`

containing information for all books on the website.

## Learning Outcomes

This project demonstrates:

- HTTP requests with Requests
- HTML parsing with BeautifulSoup
- Data extraction from web pages
- Data storage using Pandas
- CSV and JSON export
- Pagination handling
- Python loops and dictionaries

## Author

Jehosaphat Brobbey Impiani

Codveda Data Science Internship