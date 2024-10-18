# What is in this repository: <br><br>

This repository includes ingestion from the google local data found here: https://cseweb.ucsd.edu/~jmcauley/datasets.html#google_local <br><br>

The review_ingestion.ipynb contains code to take a reviews.json file from the data folder and ingest into a pandas data frame.
It also creates a pics data frame that has each review_id related to a pic_url <br><br>

The business_ingestion.ipynb contains code to take a business.json file from the data folder and convert into business and categories pandas dataframe. 
<br><br>

In the zipped data folder, there will already be examples in the data/ingested folder of these resulting files as well as examples of the actual raw json files,
specifically from Pennsylvania local reviews. In this case, the meta-Pennsylvania.json has the business data and the review-Pennsylvania_10.json holds a subset of all the reviews in pennsylvania.
The full review dataset may require greater processing power. <br><br>

The raw data files themselves are too large to be committed so included are the end dataframes for the Pennsylvania subset.
