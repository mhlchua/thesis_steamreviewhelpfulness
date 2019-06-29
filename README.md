# thesis_steamreviewhelpfulnesss
This repository includes the files and code used for my thesis about <i> Predicting the helpfulness of Steam reviews using peripheral and central features and a distinction between free and paid games </i> for Rotterdam School of Management, Erasmus University Rotterdam (MSc. Marketing Management).

Little notes on the files:
- All the important data can be found in a csv format in the folder "Data set csv files". 
- The scraped products and reviews raw data can be found in a JSON format in the folder "Reviews products JSON files"
- The thesis notebook contains all the code used for loading data, pre-processing, data analysis, etc.
- The repository also includes the Scrapy script for the review spider from the <A HREF = "https://github.com/prncc/steam-scraper"> 
Steam scraper by Andre Perunicic (prncc) </A>, of which the item loader for extracting helpful votes has been slightly altered by me to make it correspond to the current Steam review lay out (2019). All rights belong to <A HREF = "https://github.com/prncc"> prncc </A> for the review spider script.
