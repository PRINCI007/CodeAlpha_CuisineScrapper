# Cuisine Scraper

A Python script that extracts structured data about **Uttar Pradesh cuisine** from Wikipedia using the **Wikipedia API**. The script collects information from key sections including **Bread, Common food, Traditional desserts, Common beverages**, and saves it in a **CSV-friendly format**.

## Features
- Uses the **Wikipedia API** for reliable data extraction.
- Parses both **list items (`<li>`) and paragraphs (`<p>`)** within each section.
- Produces a **CSV file (`uttar_pradesh_cuisine.csv`)** ready for analysis.
- Safe and reproducible without fragile HTML scraping.

## Technologies Used
- Python (`requests`, `pandas`, `BeautifulSoup`)  
- Wikipedia API

## Install dependencies
pip install requests pandas beautifulsoup4

## Open the Jupyter Notebook:
   jupyter notebook ScrapCuisine.ipynb

### Optional Notes**
- **Jupyter Notebook is required**:  

Install Jupyter Notebook if you don’t have it:
pip install notebook
   

