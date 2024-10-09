# Web Scrapping with Python 🌐 🖥️ 🛜

![web-scraping-python-img](https://github.com/user-attachments/assets/c522c4f7-bccf-4b34-8af3-11c895d154d9)

## Description:

This Python script extracts data on Asian countries from the Wikipedia page "List of Asian Countries by Area" (https://en.wikipedia.org/wiki/List_of_Asian_countries_by_area). It utilizes the requests and BeautifulSoup libraries to retrieve and parse the HTML content, then extracts country names and creates a Pandas DataFrame for further analysis.   

## Features:

- Fetches data from the specified Wikipedia page.
- Extracts country names from the table.
- Creates a Pandas DataFrame with a column named "Country".
## Installation:

This script requires the following Python libraries:

- requests
- beautifulsoup4
- pandas
### You can install them using pip:

#### pip install requests beautifulsoup4 pandas

### Usage:

- Save the code as a Python file (e.g., asian_countries_data.py).
- Run the script from your terminal.
#### python asian_countries_data.py

This will print a Pandas DataFrame containing the extracted country names.

## Output:

The output will be a Pandas DataFrame with a single column named "Country" containing the list of Asian countries retrieved from the Wikipedia page.

### Note: 
This script assumes the Wikipedia page structure is consistent. Any changes to the page layout might require adjustments to the code for accurate data extraction.

## Additional Notes:

- You can enhance this script by adding error handling to gracefully handle network issues or unexpected HTML changes.
- Consider filtering the extracted data based on specific criteria or adding additional columns to the DataFrame based on your needs.
- Feel free to modify and extend this code to suit your specific data extraction requirements.
