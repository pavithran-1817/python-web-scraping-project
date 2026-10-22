# 📚 Python Web Scraping Project

A beginner-friendly web scraping project built with Python to collect book information from the Books to Scrape practice website.

## 🎯 Project Objective

To automatically collect book names, prices, and ratings from multiple website pages and save the results in a CSV dataset for analysis.

## 🛠️ Technologies Used

- Python
- Requests
- BeautifulSoup
- CSV module

## ✨ Features

- Scrapes book information from multiple pages.
- Collects book names, prices, and ratings.
- Stores the collected information in `books.csv`.
- Supports basic price and rating analysis.

## 📂 Project Files

- `scraper.py` — Python scraping script.
- `books.csv` — Collected book dataset.
- `README.md` — Project documentation.

## ▶️ How to Run

Install the required libraries:

```bash
python -m pip install requests beautifulsoup4
```

Run the script:

```bash
python scraper.py
```

## 📊 Dataset Fields

| Column | Description |
|---|---|
| Book Name | Name of the book |
| Price (£) | Listed book price |
| Rating | Book rating |

## 📌 Data Source

[Books to Scrape](https://books.toscrape.com/) — a practice website for web scraping.

## 👨‍💻 Author

Pavithran

---

*Educational project created for learning Python web scraping and data analysis.*
