# 📚 Book Store Scraper

This project is a web scraping script built using Python.  
It extracts book data from http://books.toscrape.com for educational purposes.

---

## 🚀 Features

- Sends HTTP requests with custom headers (User-Agent)
- Parses HTML content using BeautifulSoup
- Extracts structured book information
- Handles page data extraction
- Stores scraped data into CSV file using Pandas

---

## 🛠 Tech Stack

- Python
- Requests
- BeautifulSoup (bs4)
- lxml parser
- Pandas

---

## 📂 Project Structure

```
web scraping/
│── book to scrape.py
│── requirements.txt
│── README.md
│── books.csv
```

---

## ▶️ How To Run

1. Clone the repository:
```
git clone https://github.com/yourusername/book-scraper.git
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Run the script:
```
python book_scraper.py
```

After running, a CSV file containing book data will be generated.

---

## 📌 What I Learned

- Working with HTTP requests and response handling
- HTML parsing and element targeting
- Data extraction and structuring
- Exporting scraped data into CSV format
- Basic web scraping best practices

---

## ⚠️ Disclaimer

This project is created for educational purposes only.
The website used allows scraping for practice and learning.

---
