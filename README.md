# IMDb Top 250 Movie Data Scraper

## 📌 Project Overview
The IMDb Top 250 Movie Data Scraper is a Python-based web scraping project that extracts movie information from IMDb's Top 250 chart. It uses Selenium to automate browser interaction and Pandas to organize the collected information into a CSV file.

## 🎯 Objectives
- Extract the Top 250 movies listed on IMDb.
- Collect movie rank, title, and rating.
- Store the extracted data in a structured CSV file.
- Make movie data easier to analyze and use for visualization.

## 🛠️ Technologies Used
- **Python** – Programming language
- **Selenium** – Browser automation and web scraping
- **WebDriver Manager** – ChromeDriver management
- **Pandas** – Data processing and CSV creation
- **IMDb** – Source of movie data

## ✨ Features
- Automatically opens IMDb's Top 250 chart in Chrome.
- Extracts movie rankings, titles, and ratings.
- Checks whether all 250 movies have been collected.
- Exports the extracted information to a CSV file.
- Handles IMDb human verification when required.

## 📂 Project Structure
```text
imdb_scraper/
├── imdb.py
├── imdb_top_250.csv
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository
```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project Folder
```bash
cd imdb_scraper
```

### 3. Install Required Libraries
```bash
python -m pip install selenium webdriver-manager pandas
```

### 4. Run the Project
```bash
python imdb.py
```

If needed, use:
```bash
py imdb.py
```

## 📊 Output
The scraped movie information is saved in `imdb_top_250.csv`.

The CSV file contains the following columns:

| Column | Description |
|---|---|
| Rank | Movie's position in the Top 250 chart |
| Title | Name of the movie |
| Rating | IMDb movie rating |

## 🚀 Future Enhancements
- Create an interactive dashboard for movie data visualization.
- Analyze movie rating distributions.
- Add more movie details, such as release year and genre.
- Generate insights from the collected movie dataset.

## ⚠️ Notes
- Google Chrome must be installed.
- An active internet connection is required.
- IMDb's website structure and verification requirements may change, which can affect scraping.
- Use this project responsibly and respect IMDb's terms of use and applicable access restrictions.

## 👩‍💻 Project Purpose
This project demonstrates practical applications of Python, web scraping, browser automation, and data handling.

---
**Developed as a Python Web Scraping Project.**
