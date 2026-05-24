# 📚 Quotes Web Scraper

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup4-Scraping-green)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-lightblue)
![Excel](https://img.shields.io/badge/Microsoft-Excel-darkgreen)

---

## 📌 About

This project scrapes famous quotes, authors, and tags from
[quotes.toscrape.com](http://quotes.toscrape.com) using Python
and exports the cleaned data into a professionally formatted
Excel file with charts and analysis.

---

## ✨ Features

- Scrapes 100+ quotes across multiple pages automatically
- Extracts quote text, author name, and tags
- Handles special character encoding (é, ü, ñ etc.)
- Saves raw data to CSV
- Exports to formatted Excel (.xlsx)
- Auto row numbering
- Frozen styled header row
- Top 10 Authors bar chart (matplotlib)
- Landscape print-ready Excel layout

---

## 📁 Project Structure

```
Quotes-Scraper/
│
├── data/
│   └── quotes.csv              # Raw scraped data
│
├── output/
│   └── quotes_formatted.xlsx   # Final Excel output
│
├── Quotes_Scraper.ipynb        # Main Jupyter Notebook
├── requirements.txt            # Python dependencies
└── README.md
```

---

## ⚙️ How It Works

```
1. requests  →  sends HTTP GET to quotes.toscrape.com
2. BeautifulSoup  →  parses HTML, extracts quotes/authors/tags
3. Loops through all pages using next button link
4. pandas  →  stores and cleans the data
5. Saves to data/quotes.csv
6. matplotlib  →  generates Top 10 Authors bar chart
7. openpyxl  →  exports styled Excel file to output/
```

---

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/quotes-scraper-excel
cd quotes-scraper-excel

# Install dependencies
pip install -r requirements.txt

# Open Jupyter Notebook
jupyter notebook Quotes_Scraper.ipynb
```

---

## 📦 Requirements

```
requests
beautifulsoup4
pandas
matplotlib
openpyxl
jupyter
```

---

## ▶️ Usage

1. Open `Quotes_Scraper.ipynb` in Jupyter or VS Code
2. Click **Run All**
3. Folders `data/` and `output/` are created automatically
4. Check `data/quotes.csv` for raw scraped data
5. Check `output/quotes_formatted.xlsx` for final Excel file

---

## 📊 Output Preview

### Excel File
- All quotes with author and tags
- Color-coded styled headers
- Wrap text — all columns visible

### Bar Chart
- Top 10 most quoted authors
- Generated with matplotlib

---

## 🌐 Data Source

[quotes.toscrape.com](http://quotes.toscrape.com)
— A sandbox website designed for practicing web scraping.

---

## 🧰 Tools & Libraries Used

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| Jupyter Notebook | Development environment |
| requests | HTTP requests |
| BeautifulSoup4 | HTML parsing |
| pandas | Data handling & CSV export |
| matplotlib | Bar chart visualization |
| openpyxl | Excel file formatting |
| VS Code | Code editor |

---

## 📝 License

MIT License — free to use and modify.

---

## 🙋‍♂️ Author

Made with ❤️ as a data scraping & Excel formatting project.
```
