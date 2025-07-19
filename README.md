# 📰 BBC News Headlines Scraper

This project is a Python-based web scraper that fetches the latest headlines from the [BBC News](https://www.bbc.news/) website. It uses the `requests` and `BeautifulSoup` libraries to extract headlines from the homepage and saves them into a `.txt` file.

# 📌 Objective

- Automate the process of collecting top news headlines from a public website.
- Learn basic web scraping using Python.

# 🔧 Tools & Libraries Used

- Python 3.6+
- `requests` - for sending HTTP requests.
- `beautifulsoup4` - for parsing HTML and extracting data.

# 📁 Project Files

BBCNewsScraper/
- bbc_scraper.py (Main script)
- bbc_headlines.txt (Output file)
- README.md 

# 🧠 How It Works

Sends an HTTP GET request to https://www.bbc.news/

- Parses the HTML content using BeautifulSoup
- Extracts all <h2 class="heading"> 
- Writes each headline to bbc_headlines.txt in numbered format

# 📝 Sample Output

1. NASA prepares for new moon landing
2. Inflation eases across Europe
3. Protests erupt in major cities
.....


