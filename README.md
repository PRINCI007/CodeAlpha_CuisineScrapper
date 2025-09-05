# Cuisine Scraper

A Python script that extracts structured data about **Uttar Pradesh cuisine** from Wikipedia using the **Wikipedia API**. The script collects information from key sections including **Bread, Common food, Traditional desserts, Common beverages, See also, and References**, and saves it in a **CSV-friendly format**.

## Features
- Uses the **Wikipedia API** for reliable data extraction.
- Parses both **list items (`<li>`) and paragraphs (`<p>`)** within each section.
- Produces a **CSV file (`uttar_pradesh_cuisine.csv`)** ready for analysis.
- Safe and reproducible without fragile HTML scraping.

## Technologies Used
- Python (`requests`, `pandas`, `BeautifulSoup`)  
- Wikipedia API

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/uttar-pradesh-cuisine-scraper.git
   cd uttar-pradesh-cuisine-scraper

## Install dependencies
pip install requests pandas beautifulsoup4
## Run the script
python scraper.py
