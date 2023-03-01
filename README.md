# ETL-pipeline-for-blinkist
ETL pipeline using undetected selenium driver to avoid being blocked by cloudflare to extract books from blinkist

## How it works
- downloaded all books links from blinkist sitemap 
- used the [`fileformater.ipynb`] to organize the links and extract the links of books i want
- Developed a simple ETL pipeline using Selenium undetected driver [`linkist.ipynb`] with full automation to read the links from [`urls.csv`]
and extract it's data to [`blinkistdata.xlsx`]


## How to run
- To run the pipeline, you will need:
  - [Git](https://github.com/mohamedehabpop/ETL-pipeline-for-blinkist.git)
  - [Selenium](https://pypi.org/project/selenium/)
