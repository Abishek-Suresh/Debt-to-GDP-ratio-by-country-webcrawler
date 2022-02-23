# Debt-to-GDP-ratio-by-country-webcrawler

Used a webcrawler using scrapy to scrap the debt to GDP ratio of the countries,from the website: https://worldpopulationreview.com/countries/countries-by-national-debt

Repository Link: https://github.com/Abishek-Suresh/Debt-to-GDP-ratio-by-country-webcrawler

## Tools
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge)
![Scrapy](https://img.shields.io/badge/Scrapy-FFD43B?style=for-the-badge&logo=Scrapy)

## To install scrapy
    
    pip install scrapy
    
## To create a new project
    
    scrapy startproject national_debt
    
## To generate spider
    
    scrapy gen spider gdp_debt https://worldpopulationreview.com/countries/countries-by-national-debt

## To Run the Spider

    scrapy crawl gdp_debt

## Export output as CSV, Json, or XML

    scrapy crawl countries -o <filename.extension>
