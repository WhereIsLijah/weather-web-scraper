# Weather Location Scraper with Selenium

This Python script automates fetching the current temperature for a specified location from "https://weather.com". It demonstrates practical web scraping and browser automation using Selenium to interact with web elements, handle dynamic content, and extract data.

## Prerequisites

Ensure you have the following installed:
- Python 3.x
- Selenium WebDriver
- ChromeDriver (or any WebDriver compatible with your preferred browser)

## Setup & Installation

1. **Install Python 3**: If not already installed, download and install Python 3 from the official [Python website](https://www.python.org/downloads/).

2. **Install Required Python Libraries**: Run the following command in your terminal or command prompt to install Selenium and WebDriver Manager:
    ```bash
    pip install selenium webdriver_manager
    ```

3. **WebDriver Setup**: This script uses `ChromeDriverManager` from the `webdriver_manager` package to automatically manage the WebDriver binary. If you prefer a different browser, ensure you have the corresponding WebDriver installed.

## Running the Script

To use the script, follow these steps:

1. Open your terminal or command prompt.

2. Navigate to the directory where the script is saved.

3. Run the script using Python by executing the command below:

    ```bash
    python selenium_test.py
    ```

4. When prompted, enter the location of your choice (e.g., "Ottawa Hills") into the terminal. The script will then automatically navigate to "https://weather.com", input your specified location into the search box, select the first suggestion from the autocomplete dropdown, and after loading the weather details for the selected location, print the current temperature to the console.

For example:

```bash
Enter the location of choice: Ottawa Hills
