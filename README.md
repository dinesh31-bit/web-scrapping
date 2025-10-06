# web-scrapping
📊 Web Scraping Project – Largest Public Companies in the U.S.
🧠 Project Overview

This project involves web scraping data from Wikipedia to collect information about the largest publicly traded companies in the United States by revenue. The scraped data is processed, structured, and stored in a tabular format using Python libraries.

🌐 Data Source

Website: Wikipedia – List of Largest Companies in the United States by Revenue

⚙️ Steps Followed

Fetched the HTML Content:
Used the BeautifulSoup library to extract the required HTML content from the target Wikipedia page.

Accessed the Table Data:
The page contains multiple tables with the same class name (wikitable sortable).
I identified the correct table using its index position within the HTML structure.

Extracted Table Headers:
Retrieved all the column headers (<th>) from the selected table and stored them as table column names.

Parsed Table Rows:
Looped through all the table rows (<tr>) and extracted each data cell (<td>).
These values were collected and appended to a Pandas DataFrame.

Structured the Data:
Organized the extracted data into a clean, readable tabular format using Pandas for easy analysis and manipulation.

Data Export:
The final dataset can be saved in multiple formats such as CSV, Excel, or JSON for further use.

🧰 Tools & Libraries Used

Python

BeautifulSoup (bs4) – for HTML parsing

Requests – for fetching the web page content

Pandas – for data cleaning, organization, and storage

📁 Output

A well-structured dataset containing the list of the largest publicly traded companies in the U.S., including details such as company name, industry, revenue, and more.
