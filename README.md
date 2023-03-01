# ETL-pipeline-for-blinkist
ETL pipeline using undetected selenium driver to avoid being blocked by cloudflare to extract books from blinkist

## How it works
- downloaded all books links from blinkist sitemap 
- used the [`fileformater.ipynb`] to organize the links and extract the links of books i want
- Developed a simple ETL pipeline using Selenium undetected driver with full automation to read the links and xetract it's data 


## How to run
- To run the pipeline, you will need:
  - [Git](https://github.com/mohamedehabpop/ETL-pipeline-for-blinkist.git)
  - [Selenium](https://pypi.org/project/selenium/)
