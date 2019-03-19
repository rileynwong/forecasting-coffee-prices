# Projecting Coffee Prices in Kenya
Using data from the Nairobi Coffee Exchange for coffee prices from 2014-2018, scrape data from PDFs, and forecast future coffee prices for the 2018-2019 session.

Uses [Tabula](https://github.com/chezou/tabula-py) for data scraping and [Prophet](https://github.com/facebook/prophet/) for time-series forecasting.


### Setup
- Create and activate a new virtual environment:
  - `$ conda create -n coffee_env python=3`
  - `$ conda activate coffee_env`

- Install project dependencies:
  - `$ conda install gcc; conda install -c conda-forge fbprophet`
  - `$ pip install -r requirements.txt`


### File Overview
- [PDF_to_CSV.ipynb](PDF_to_CSV.ipynb): Jupyter notebook that parses and cleans the data from the PDF files into a CSV file.
- [Predicting_Coffee_Prices.ipynb](Predicting_Coffee_Prices.ipynb): Jupyter notebook that plots the monthly average prices for grade AA, AB, and C coffee, and forecasts the coffee prices for 2018-2019.
- [Projecting_Coffee_Prices_in_Kenya.pdf](Projecting_Coffee_Prices_in_Kenya.pdf): PDF report summarizing findings.
- [monthly_coffee_prices.csv](monthly_coffee_prices.csv): Resulting dataset from parsing PDF files.
- [pdfs/](pdfs/): Directory of original PDF files.
- [predictions/](predictions/): Directory of CSV files containing predictions for the 2018-2019 session for grade AA, AB, and C coffee.







