Before starting:
- Make sure you have all packages necessary to run. Follow the commands in the Jupyter window to install:
!pip install pandas
!pip install requests
!pip install beautifulsoup4
!pip install ssl
!pip install urllib3

Description:
The program uses web scraping to collect data from Imdb.com on the 250 best movies of all time.
Data is collected on:
- Title,
- Publication date,
- Rating,
- Number of votes,
Using BeautifulSoup.

Then the data is cleared of unnecessary characters (e.g. brackets from "Year") and converted from string data to integer/float data.
Then the data is written to the DataFrame and saved to an Excel file. As a result, there is no need to perform web scraping each time the program is started, so we do not unnecessarily burden the IMDB server.
Then, information obtained from raw movie data is shown.

We obtain information such as:
- Mean,
- Standard deviation,
- Quartiles,
- Maximum and minimum value,
- Number of occurrences of a given rating,
- Number of films produced in a given year and decade,
- Number of votes,
and more.

The information is presented in tables, graphs and in a descriptive form (interpretation of results)
