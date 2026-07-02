# BBC News Headlines Web Scraper

## Overview
This project is a simple Python web scraper that extracts the latest **BBC News** headlines from the BBC News website using the `requests` and `BeautifulSoup` libraries. The extracted headlines are saved into a text file named `headlines.txt`.

## Features
- Fetches the BBC News homepage.
- Extracts all `<h2>` headlines.
- Removes duplicate headlines.
- Saves headlines to `headlines.txt`.
- Handles HTTP request errors gracefully.

## Technologies Used
- Python 3
- Requests
- BeautifulSoup4

## Requirements
Install the required libraries:

```bash
pip install requests beautifulsoup4
```

## How to Run
1. Save the Python script as `main.py`.
2. Install the required libraries.
3. Run the program:

```bash
python main.py
```

## Output
The program creates a file named `headlines.txt` containing all extracted BBC News headlines.

Example console output:

```text
Successfully saved 43 headlines to headlines.txt
```

## Project Structure

```
project/
│── main.py
│── headlines.txt
└── README.md
```

## Future Enhancements
- Save data in CSV or JSON format.
- Scrape headlines from multiple news websites.
- Add timestamps to the saved headlines.
- Schedule automatic scraping.

## Author
