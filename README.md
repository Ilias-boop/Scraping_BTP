# Project Overview

This project is a web scraper designed to extract testimonials from individuals who have shared their experiences of sexual assault or related crimes on the website BalanceTonPorc. The goal is to collect and structure this data for research, analysis, and awareness purposes while ensuring responsible and ethical scraping practices.

# Features

Scrapes testimonial articles from multiple pages of the website.

Extracts key details, including:

- Title of the testimonial

- Theme or category of the post

- Full text of the testimonial

- Date of publication

Implements User-Agent rotation to minimize detection.

Uses session persistence to maintain cookies and headers.

Respects server load by implementing randomized delays between requests.

Saves scraped data as a structured CSV file.

# Dependencies

The following Python libraries are required:
```
pip install requests beautifulsoup4 pandas
```
# Installation and Usage

1. Clone the repository
```
git clone https://github.com/yourusername/testimonial-scraper.git
cd testimonial-scraper
```
2. Install dependencies
```
pip install -r requirements.txt
```
3. Run the script
```
python scraper.py
```
4. View results

The scraped testimonials will be saved in `scraped_articles.csv`.
