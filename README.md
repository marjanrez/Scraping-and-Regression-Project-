![housing-market](https://user-images.githubusercontent.com/42986304/163648924-4c9a4c01-e824-4405-a2c6-bc087a91437c.jpeg)

# Scraping and Regression Project (Metis Project 2)

The project required web scrapping and analysis of resulting data using regression, the form of regression was based on the data collected and the feature engineering necessary to analyze the data in regression.
I focused on real estate sales price in different cities of The United States, as listed on the Century21 website. Century21 is a real-estate property website that displays the information related to different properties, which I scraped the website using BeautifulSoup library.  
Then, I did regularization and feature engineering on data and analyzed house price predications on different parameters, and evaluated my model to get the best result for my predictions. I used linear regression with K-fold cross validation to predict the Target using the Features listed below.

#### Target :
- Price
#### Features:
-   Beds
- 	Baths	
- 	Size	
- 	Address	
- 	City	
- 	State	
- 	Zipcode
- 	Region


#### Data collected from:
https://www.century21.com 


### Packages required:
- Python 
- BeautifulSoup
- Requests
- Matplotlib
- Pandas
- Numpy
- Sklearn

#### There are three Jupyter Notebooks:
- Webscrap century21 preprocessing : contains python code for scraping the century21 website and parsing data, initial data cleaning and organizing.
- Analysis and visualization : contains python code of the final data cleaning, EDA, analysis and data visualization done for this project.
- Regression_Analysis : contains modelings and evaluations

There are also two pdf files:
- Presentation slides used to present this project 
- Write up the project.

##### some other works to get ideas:
- https://github.com/ar2849/Metis-Project-Two/blob/main/Project%20-%202%20Metis%20Deck.pdf
- https://medium.com/@websitescraper.com/how-to-scrape-zillow-for-real-estate-listings-using-python-and-lxml-aac3eb0c26d7
- https://github.com/CodeSigma91/Project_WebScraping/blob/master/analysis%20and%20visualization.ipynb
- https://github.com/jiveshs98/Python-Scraping-Real-Estate-Data/blob/master/century21.ipynb






