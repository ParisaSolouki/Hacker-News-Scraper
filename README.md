# 📰 Hacker News Front Page Web Scraping (Python)

## 📌 Project Overview

This project demonstrates how to scrape real-world data from a live website using Python.  
It extracts structured information from the **Hacker News front page** and saves it into a CSV file for analysis.

The project is designed as a learning and portfolio exercise to practice:

- Web scraping fundamentals  
- Understanding real HTML structures  
- Handling missing data safely  
- Organizing scraped data into a clean dataset  

---

## 🔍 Data Extracted

For each news item on the Hacker News homepage, the script collects:

- **Rank** – Position of the news item on the front page  
- **Title** – News headline  
- **Link** – URL of the article  
- **Score** – Number of upvotes  
- **Author** – Username of the submitter  
- **Age** – Time since submission  
- **Comments** – Number of comments  

---

## 🛠 Tools & Libraries Used

- Python  
- `requests` – Download webpage content  
- `BeautifulSoup` (`bs4`) – Parse and navigate HTML  
- `pandas` – Create DataFrame and export CSV  

---

## 📂 Project Structure

```text
Hacker-News-Web-Scraping/
│
├── hackernews_scraper.py
├── hackernews_frontpage.csv
└── README.md

---

## 🚀 How to Run
### 1️⃣ Install required libraries

```bash
pip install requests beautifulsoup4 pandas

### 2️⃣ Run the scraper
python hackernews_scraper.py

---

## 📄 Output
hackernews_frontpage.csv





