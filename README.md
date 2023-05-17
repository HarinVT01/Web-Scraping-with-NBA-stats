# Web-Scraping-with-NBA-stats
#### Scraped the NBA data and done some data preprocessing steps to get best predicted output and ML models are used for prediction.

## It includes 3 major steps: 
- Web Scraping.
- Data Preprocessing.
- Prediction.

## Web Scraping
1. Install Libraries
  - pandas
  - requests
  - BeautifulSoup
  - selenium

2. Make request to NBA websites in which you want to scrap the informations. The data collected are:
- mvp
- player
- teams
3. Use BeautifulSoup library used to scrap the data
4. Convert the scraped data into dataframe.
5. Convert the dataframe to csv.

## Data Preprocessing
1. Load mvp dataset
2. Load player dataset
3. Remove unwanted attributes in player dataset
4. Combine mvp and player data
5. Load team dataset
6. Remove unwanted attributes in team data
7. Convert the string attributes to numeric attribute
8. Combine team, player and mvp data
