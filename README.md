# olx-car-cover-scraper

# OLX Car Cover Scraper

This is a simple Python script that scrapes search results for **"Car Cover"** listings on [OLX India](https://www.olx.in/items/q-car-cover) and saves them to a CSV file.

## 🔧 Features
- Scrapes listing titles, prices, locations, and links
- Saves results in `car_cover_olx_results.csv`
- Uses `requests` and `BeautifulSoup` for web scraping

## 📦 Requirements
- Python 3.6+
- `requests`
- `beautifulsoup4`

Install dependencies:
```bash
pip install requests beautifulsoup4
```

## 🚀 Usage
```bash
python olx_car_cover_scraper.py
```
After running the script, check the generated `car_cover_olx_results.csv` file for results.

## 📁 Output
Example output in CSV:
```
Title,Price,Location,Link
"Premium Car Cover","₹899","Mumbai","https://www.olx.in/..."
...
```

## ⚠️ Note
- OLX page structure may change, so scraping logic may need updates.
- Always ensure compliance with OLX’s terms of service when scraping public data.

## ✍️ Author
Pratham Patil
