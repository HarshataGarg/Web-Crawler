## Mini Project-7: Web Crawler (Email Scraper)

- 📌 **Goal**: Extract all emails available on a website and save them in a CSV file.
- 🔗 **Input**: Just enter the **sitemap URL** of the target website.
- 📥 **Output**: All found email addresses will be stored in a structured `.csv` file.
- ⚙️ **Functionality**:
  - Parses the sitemap.
  - Crawls all reachable pages listed.
  - Extracts valid email patterns using regex.
  - Avoids duplicates.
- 🛠️ **Technologies Used**: Python, `requests`, `BeautifulSoup`, `re`, `csv`.
