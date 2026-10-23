# 📚 Python Web Scraping & Book Price Analysis

A beginner-friendly data analytics project that collects book information from a website using Python, stores the data in a CSV file, and analyzes book prices using data analysis and visualization techniques.

## 📌 Project Overview

This project demonstrates how web scraping can be used to automatically collect structured data from a website instead of manually copying information.

The project scrapes book details from the practice website **Books to Scrape**, saves the collected information into a CSV file, performs basic price analysis, and visualizes the results using Google Sheets charts.

## 🎯 Objectives

- Learn the fundamentals of web scraping using Python.
- Extract book names, prices, and ratings from web pages.
- Collect data across multiple pages automatically.
- Store the collected information in a CSV file.
- Analyze book prices using basic statistical calculations.
- Create charts to understand and present the results.
- Practice GitHub version control and project documentation.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Requests | Fetch web page content |
| BeautifulSoup | Parse HTML and extract book information |
| Pandas | Organize and analyze tabular data |
| CSV | Store the scraped dataset |
| Google Sheets | Create charts and visualize book prices |
| GitHub | Store and share the project |

## 🌐 Data Source

**Website:** [Books to Scrape](https://books.toscrape.com/)

Books to Scrape is a practice website designed for learning web scraping. It provides book information such as titles, prices, ratings, and availability.

## ⚙️ Project Workflow

1. **Access the website** — Python Requests retrieves the website's HTML content.
2. **Parse HTML** — BeautifulSoup identifies the relevant elements on each page.
3. **Extract book details** — The scraper collects each book's title, price, and rating.
4. **Navigate pages** — The script moves through multiple pages to collect more records.
5. **Save the dataset** — The extracted information is stored in `books.csv`.
6. **Analyze prices** — Python calculates the highest, lowest, and average prices.
7. **Visualize results** — Google Sheets is used to create charts for book price comparison.
8. **Publish the project** — The source code, dataset, documentation, and analysis output are uploaded to GitHub.

## 📂 Project Structure

```text
python-web-scraping-project/
│
├── scraper.py
│   └── Python script for collecting book information
│
├── books.csv
│   └── Dataset containing scraped book details
│
├── README.md
│   └── Project documentation
│
└── Book_Price_Analysis.pdf
    └── Charts and book price analysis output
```

*Note: The PDF filename above is an example. Use the exact filename shown in your GitHub repository.*

## 📊 Dataset Description

The generated `books.csv` file contains the following columns:

| Column | Description |
|---|---|
| Book Name | Title of the book |
| Price (£) | Price of the book in pounds sterling |
| Rating | Rating displayed on the website |

### Sample Dataset

| Book Name | Price (£) | Rating |
|---|---:|---|
| A Light in the Attic | 51.77 | Three |
| Tipping the Velvet | 53.74 | One |
| Soumission | 50.10 | One |
| Sharp Objects | 47.82 | Four |
| Sapiens | 54.23 | Five |

*These are illustrative sample records from the earlier scraping output; the final CSV file is the source of truth for the complete dataset.*

## 📈 Data Analysis Results

The completed scraping run reported the following results:

| Metric | Result |
|---|---:|
| Total books collected | 1,000 |
| Highest book price | £59.99 |
| Lowest book price | £10.00 |
| Average book price | £35.07 |
| Output file | `books.csv` |

These statistics help summarize the price range and general pricing pattern of the collected books.

## 📉 Data Visualization

Two charts were created using Google Sheets.

### 1. Book Price Analysis

- **Chart type:** Column chart
- **Purpose:** Compare the prices of the first 10 books in the dataset.
- **X-axis:** Book names
- **Y-axis:** Book prices in pounds sterling

This chart makes it easier to compare prices across the selected books.

### 2. Top 10 Most Expensive Books

- **Chart type:** Bar chart
- **Purpose:** Compare the prices of the 10 highest-priced books.
- **Categories:** Book names
- **Values:** Book prices in pounds sterling

This chart highlights the most expensive books in the dataset.

**Analysis output:** See the uploaded `Book_Price_Analysis.pdf` file in this repository for the charts, if that is the filename you used.

## 💻 Installation and Execution

### Prerequisites

- Python 3 installed on your computer
- Internet connection
- A code editor such as Visual Studio Code

### Step 1: Clone the repository

```bash
git clone https://github.com/pavithran-1817/python-web-scraping-project.git
```

### Step 2: Open the project folder

```bash
cd python-web-scraping-project
```

### Step 3: Install the required libraries

```bash
python -m pip install requests beautifulsoup4 pandas
```

### Step 4: Run the scraper

```bash
python scraper.py
```

### Step 5: View the results

After the script completes successfully, open `books.csv` in Excel, Google Sheets, or another spreadsheet application to inspect the collected records.

The terminal should display a completion message similar to:

```text
--- SCRAPING COMPLETED ---
Total books collected: 1000
CSV saved as books.csv
Highest price: 59.99
Lowest price: 10.0
Average price: 35.07
```

*Expected output is shown above. Actual results may vary if the website's content or the script changes.*

## 🧠 Key Learnings

Through this project, I learned:

- How to send HTTP requests to retrieve web pages.
- How to inspect and parse HTML using BeautifulSoup.
- How to extract structured data from repeated HTML elements.
- How to scrape data across multiple pages.
- How to save collected data in CSV format.
- How to calculate basic descriptive statistics for prices.
- How to build charts for data visualization.
- How to upload and document a Python project on GitHub.

## 🚀 Future Improvements

- Add error handling for failed requests and missing fields.
- Store scraped data in a database.
- Analyze book ratings alongside prices.
- Create an interactive dashboard using Streamlit.
- Automate scraping and data updates.
- Add more visualizations and summary statistics.

## ⚠️ Disclaimer

This project was developed for educational purposes using the Books to Scrape practice website. Always respect a website's terms of use, scraping policies, and rate limits when collecting online data.

## 👨‍💻 Author

**Pavithran**

GitHub: [@pavithran-1817](https://github.com/pavithran-1817)

## ⭐ Conclusion

This project demonstrates a complete beginner-level data workflow, from collecting information through web scraping to storing, analyzing, visualizing, and documenting the results.

It combines Python programming, data handling, basic statistical analysis, data visualization, and GitHub project management in one practical project.

If you find this project useful, feel free to explore the repository and learn from the implementation.
