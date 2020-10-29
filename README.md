
![Image](https://user-images.githubusercontent.com/63467553/97612809-2bb8ca00-1a18-11eb-9eb3-65741bc780fb.png)


## Motivation :blush:
This is my final project within the Data Analytics Bootcamp in Ironhack Madrid (2020 Part Time version). 

## Overview :computer:
Amazon is the most important eretailer in Spain, however, when it comes to analysing product data in Amazon, the eretailer's analysis tool called **Amazon Vendor Central** is not that simple nor that intuitive. Indeed you can use it to keep track of sales, logistic monitorisation or search trends analysis, however, when it comes to product and sentiment analysis, the data gap is still taking place. **Scrapey** has been created in order to be able to make it easier to analyse Amazon's product data. With Scrapey you will be able to get all the insightful data that you need in order to make business decisions within Amazon, as well as get all product reviews and sentiment analysis. 

---

## Data sources :scroll:
 - Amazon product list containing the following products:
   - 128 smartphones
   - 115 TVs
   - 81 tablets
   - 62 screens
   - 42 appliances
   - 20 earphones
   - 15 soundbars

## Requirements :arrow_forward:

You will need to install and import or have already installed and imported the following Python libraries and tech stack in order to be able to analyse the data:
- Data scraping:
    - BeautifulSoup
    - Requests
- Data cleaning and modeling:
    - Pandas
    - Langdetect
    - NLP model: Bert
- Data visualisation:
    - Matplotlib
    - Tableau
    
## Folder structure :open_file_folder:
```
└── project   
    └── amazon_urls
        ├── amazon_appliances.csv
        ├── amazon_earphones.csv
        ├── amazon_screen_storage.csv
        ├── amazon_smartphones.csv
        ├── amazon_soundbars.csv
        ├── amazon_tablets.csv
        ├── amazon_tvs.csv
    ├── notebook
        ├── scraper_ratings.ipynb
    ├── .gitignore
    ├── README.md
    ├── requirements.txt
```
## Main blockers :tada:
    - Captcha blocker - Make sure to keep time.sleep as long as possible

## Output :pushpin:
`.csv` file with all scraped data and Tableau public dashboard in order to visualise and keep track of data evolution. 

## Disclaimer :electric_plug:
Code not to be forked or cloned without agreement 


