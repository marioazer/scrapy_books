# 📚 Scrapy Books – Web Scraping Project with Scrapy

This project is a practical implementation of web scraping using [Scrapy](https://scrapy.org/), based on the [freeCodeCamp.org Scrapy course](https://www.youtube.com/watch?v=QblMHLvQalo) by Joe Kearney.

The goal of this project is to crawl book data from an online website and extract structured information such as titles, prices, availability, ratings, and more. This repo includes features like item pipelines, CSV export, and best practices for robust scraping.

---

## 🚀 Features

- Crawl and extract data from multiple pages
- Clean and structure data using Scrapy Items and Pipelines
- Export data to CSV
- Handle fake headers and user-agents
- Rotating proxies (optional)
- Scalable architecture ready for deployment to the cloud

---

## 🕸 Example Data Extracted

- Book Title
- Price
- Rating
- Availability
- Product Page Link

---

## 📂 Project Structure

```bash
scrapy_books/
├── scrapy_books/          # Scrapy project core
│   ├── __init__.py
│   ├── items.py           # Define scraped data structure
│   ├── middlewares.py
│   ├── pipelines.py       # Process and clean scraped data
│   ├── settings.py        # Scrapy project settings
│   └── spiders/           # Spiders directory
│       └── books_spider.py  # Main spider
├── output.csv             # Exported data (if saved as CSV)
├── README.md              # This file
