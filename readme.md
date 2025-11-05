# Bookstore Data Scraper and Automation

This project scrapes book information from **https://books.toscrape.com**, processes the data, and automatically generates spreadsheets and a summary PDF report.  
It demonstrates **real-world data workflow automation** using Python.

## ✅ Features
- Web scraping using `requests` + `BeautifulSoup`
- Extracts **Title**, **Price**, and **Rating**
- Cleans and structures data with `pandas`
- Saves output in **CSV** and **Excel (.xlsx)** formats
- Generates a **PDF report** including:
  - Total books scraped
  - Average book price
  - Top 5 most expensive books

## 🛠️ Technologies Used
| Purpose | Library |
|--------|---------|
| Web Scraping | `requests`, `BeautifulSoup4` |
| Data Cleaning & Export | `pandas`, `openpyxl` |
| PDF Report Generation | `FPDF` |

## 📂 Output Files
| File | Description |
|------|-------------|
| `books.csv` | Raw dataset exported to CSV |
| `books.xlsx` | Well-structured Excel dataset |
| `report.pdf` | Automated summary report |

## 📸 Example Use Cases
- Price analysis for e-commerce products
- Market research automation
- Competitor monitoring
- Data cleaning and reporting pipeline

## 🏁 How to Run
```bash
pip install -r requirements.txt
python scraper.py
