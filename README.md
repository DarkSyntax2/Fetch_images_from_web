# Fetch_images_from_web

This is a simple Flask web application that allows users to input a URL, scrape images from the webpage using Selenium and BeautifulSoup, and download them as a ZIP file.

## Features

- Scrapes all images from a specified webpage.
- Downloads images into a local folder.
- Provides a ZIP file containing all the images for easy download.
- Runs in headless mode using Selenium.

## Prerequisites

Before running this application, ensure you have the following installed:

- Python 3.x
- Google Chrome
- ChromeDriver (automatically managed by `webdriver_manager`)

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/DarkSyntax2/Fetch_images_from_web.git
   cd Fetch_images_from_web
   ```

2. (Optional but recommended) Create a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

## Usage

1. Run the Flask application:

   ```bash
   python app.py
   ```

2. Open a web browser and go to:

   ```url
   http://127.0.0.1:5000/
   ```

3. Enter a URL, click submit, and download the scraped images as a ZIP file.

## Dependencies

- Flask
- Selenium
- Webdriver Manager
- Requests
- BeautifulSoup
- Zipfile
