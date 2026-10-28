# 🐍 Python Job Listings Scraper

A lightweight web scraper built with Python that extracts job listings (Titles, Companies, Locations, and Application Links) from a target website and exports the structured data directly into a CSV file.

This project was built as part of the [roadmap.sh](https://roadmap.sh/) Python developer learning path to practice web scraping fundamentals.

---

## 🚀 Features

* Fetches live HTML content using the `requests` library.
* Parses and navigates the HTML structure using `BeautifulSoup`.
* Extracts specific details for each job listing:
  * **Job Title**
  * **Company Name**
  * **Location**
  * **Direct Apply Link**
* Exports all scraped data cleanly into a `job_listings.csv` file for easy viewing in Excel or Google Sheets.

---

## 🛠️ Tech Stack

* **Python 3.x**
* **Requests** (HTTP library)
* **BeautifulSoup4** (HTML parsing)
* **CSV** (Built-in Python module for file generation)

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/your-repo-name.git](https://github.com/YOUR_USERNAME/your-repo-name.git)
   cd your-repo-name
   ```
2. **Install required dependencies:**
  ```bash
  pip install requests beautifulsoup4
  ```
3. **Run the scraper:**
  If you are running it as a standard Python script:

  ```Bash
  python scraper.py
  (Alternatively, you can run the provided Jupyter Notebook Python job listing scraper.ipynb step by step).
  ```
📂 Output  
Once executed successfully, the script will generate a file named job_listings.csv in your project directory containing all the scraped listings.

💡 What I Learned
How to send HTTP GET requests and check response status codes.

How to inspect web page DOM elements and locate target tags using developer tools.

How to use CSS selectors and classes with BeautifulSoup to extract clean text and attribute values (href).

How to write and format data into CSV files using Python.

🤝 Contributing  
Contributions, issues, and feature requests are welcome! Feel free to check out the issues page.


### Quick tip before uploading:
Make sure to replace `YOUR_USERNAME/your-r
