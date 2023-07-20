# Python Web Scraping for Job Listings on TimesJobs

In this project, I used Python web scraping techniques to extract job listings from the TimesJobs website using the BeautifulSoup library. Here are the key steps I followed:

## Importing Libraries:

- Imported the required libraries, BeautifulSoup and requests, to perform web scraping.

## Web Scraping:

- Fetched the HTML content of the job search page for Python-related jobs using the `requests.get()` method.
- Created a BeautifulSoup object to parse the HTML content and extract relevant information.

## Extracting Job Details:

- Utilized BeautifulSoup to find all the job listings on the page.
- Extracted the company name, required skills, published date, and more info link for each job listing.
- Stored the extracted data in a list of dictionaries.

## Displaying and Storing Data:

- Printed the details of each job listing, including company name, required skills, published date, and more info link.
- Created a Pandas DataFrame to store the extracted data in tabular form.
- Exported the DataFrame to an Excel file named "times_job14.xlsx" for further analysis.

The code demonstrates how to perform web scraping to gather job-related data efficiently. This skill is useful for automating repetitive tasks and extracting valuable
