# Scrape Clinical Data
## Disclaimer: 
This project is intended for **educational and research purposes only**.Ensure compliance with the target website’s terms of service before scraping.

## Project Overview: 
This project is a **multi-level web scraping pipeline** designed to extract clinic data from the archived **MyFootDr – Our Clinics** webpage via the Wayback Machine.
It systematically navigates through:
• Regions
• Clinics within regions
• Individual clinic pagesand compiles the extracted data into a structured CSV dataset.

## Key Highlights
• Automated traversal of hierarchical web pages (Region → Clinic)
• Works on archived snapshots (Wayback Machine compatible)
• Lightweight and dependency-efficient
• Clean modular scraping functions
• CSV-based structured output
• Easily extendable for deeper data extraction

## Tech Stack
• Python 3.x
• requests (HTTP handling)
• BeautifulSoup (HTML parsing)
• CSV module (data storage)

## Customization
You can easily extend this scraper to extract:
• Address
• Phone number
• Email
• Services offered
• Opening hours

##  Inspiration
This project demonstrates how **structured data pipelines + web scraping** can be used for:
• Healthcare directory analysis
• Market research
• Location-based data aggregation
• AI/ML dataset creation

## Important Notes
• Designed specifically for **archived (Wayback Machine) pages**
• Includes request delays to ensure polite scraping
• Structure may vary if scraping a live site

