# Amazon Data Scrape, Data Analysis

### 1. amazon_scrape 

Notebook scrapes product description, rating, review count, price and oritinal product image size of the first 50 pages of products, given a search term on amazon. 

Notebook uses beautifulsoup and selenium via chromedriver to scrape the data and saves to a csv file: results.csv

### 2. amazon_data_clean 

Notebook to clean data 


### 3. amazon_EDA

Exploratory Data Analysis on scraped amazon product data on search term: 'Women's Necklances'.
Explores correlations between price, rating, review count, description length and image quality

### Some Tableau visualisations
<p align="center">
<img width="608" alt="Screenshot 2022-04-15 at 01 49 54" src="https://user-images.githubusercontent.com/71874390/163527932-d0d88241-d63d-4163-99e6-bbad32ce6720.png">
<img width="800" alt="Screenshot 2022-04-15 at 01 38 47" src="https://user-images.githubusercontent.com/71874390/163527487-0d3a90a5-ef6e-4652-b53e-f692256eaf77.png">
<img width="800" alt="Screenshot 2022-04-15 at 01 58 28" src="https://user-images.githubusercontent.com/71874390/163527901-06ea88f0-382e-4a9f-8aff-44d2113ea68c.png">
<img width="800" alt="Screenshot 2022-04-15 at 01 58 40" src="https://user-images.githubusercontent.com/71874390/163527906-53625476-c35e-4485-9a18-75a66c508ab0.png">
</p>

Image Quality and Review Count Show (relatively) strongest correlation

Further visualisations carried out using matplotlib and sns in notebook
