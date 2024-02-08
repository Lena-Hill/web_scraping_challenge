# Mars Data Web Scraping Project

This project involves scraping data from various sources related to Mars, including news articles and weather data, and analyzing the collected data. It consists of two parts:

1. **Scraping Mars News Articles**: Extracts titles and preview text from Mars news articles.
2. **Scraping and Analyzing Mars Weather Data**: Scrapes and analyzes weather data from Mars, including temperature and atmospheric pressure.

## Dependencies

- [Splinter](https://splinter.readthedocs.io/en/latest/): Python library for automated browser interaction.
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/): Python library for parsing HTML and XML documents.
- [Pandas](https://pandas.pydata.org/): Python library for data manipulation and analysis.

## Part 1: Scraping Mars News Articles

- Uses automated browsing with Splinter to visit the Mars news website.
- Utilizes Beautiful Soup to extract titles and preview text from news articles.
- Stores the scraped data in Python data structures.

## Part 2: Scraping and Analyzing Mars Weather Data

- Uses automated browsing with Splinter to visit the Mars temperature data website.
- Scrapes weather data from the HTML table using Beautiful Soup.
- Analyzes the dataset using Pandas functions to answer specific questions.
- Visualizes the results using matplotlib.

## Usage

1. Ensure that all dependencies are installed (`pip install -r requirements.txt`).
2. Run `part_1_mars_news.ipynb` to scrape and analyze Mars news articles.
3. Run `part_2_mars_weather.ipynb` to scrape and analyze Mars weather data.
4. View the results and analysis in the respective Jupyter Notebooks.

## Files Included

- `part_1_mars_news.ipynb`: Jupyter Notebook for scraping and analyzing Mars news articles.
- `part_2_mars_weather.ipynb`: Jupyter Notebook for scraping and analyzing Mars weather data.
- `mars_weather_data.csv`: CSV file containing the scraped Mars weather data.

## Author

- Lena Hill

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

    

    
