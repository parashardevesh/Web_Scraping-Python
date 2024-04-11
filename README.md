## IMDb Web Scraping Project

This project demonstrates how to perform web scraping on the IMDb website to gather data about the top 250 movies listed on IMDb. The collected data is then converted into a pandas DataFrame, cleaned, and exported as a CSV file.

#### Project Overview

1. **Fetching IMDb Web Page**: The project starts by fetching the IMDb top 250 movies web page using `urlopen` from the `urllib.request` library. The web page content is retrieved and stored as HTML using BeautifulSoup.

2. **Parsing HTML Content**: Once the HTML content is fetched, it is parsed using BeautifulSoup to extract relevant information such as movie names, release years, and runtimes.

3. **Creating DataFrame**: The extracted data is then used to create a pandas DataFrame with columns for movie names, release years, and runtimes.

4. **Cleaning Data**: The DataFrame undergoes data cleaning to remove unnecessary HTML tags and unwanted characters from the movie names.

5. **Exporting as CSV**: Finally, the cleaned DataFrame is exported as a CSV file named "Imdb_top250.csv" for further analysis or usage.

#### Tools Used

- `urllib.request`: Used to fetch web pages.
- `BeautifulSoup`: Utilized for parsing HTML content and extracting data.
- `pandas`: Used to create and manipulate DataFrames.

#### Usage

To run the project:

1. Ensure you have Python installed on your system.
2. Install required libraries: `urllib.request`, `BeautifulSoup`, `pandas`.
3. Run the Python script to fetch, parse, clean, and export IMDb data as a CSV file.

#### Conclusion

This project demonstrates a basic yet effective use case of web scraping with Python to gather data from the IMDb website. By utilizing libraries like `urllib.request` and `BeautifulSoup`, we can automate the process of data collection and extraction, making it convenient for analysis and further usage. However, it's important to be mindful of web scraping ethics and adhere to website terms of service.

#### Happy Coding!! 🙇‍♂️
