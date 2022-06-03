# reviews-seattle-airbnb
Repository for identifying the impact of reviews on price of a homestay listing.
## Motivation
In this repository, CRISP-DM steps are applied on Seattle-Airbnb-data to answer below questions:

1. Which are the top five highly rated hosts? Are all of them superhosts?
2. Are the top ten reviewing/loyal customers satisfied or in simple words have they rated on higher side or lower side than average rating?
3. What are the most correlated features with price of the listing?
4. Does review rating and cancellation policy have any influence on price? If yes how much compared to other features?
## File Description
DSND-Seattle-Airbnb.ipynb: Notebook containing the code for analysis
<br>requirements.txt: Text file containing all the libraries used with exact version
<br>Data/DSND/listings.csv: Seattle-Airbnb 2018 Listings dataset
<br>Data/DSND/reviews.csv: Seattle-Airbnb 2018 Reviews dataset
<br>Data/DSND/calendar.csv: Seattle-Airbnb 2018 calendar dataset (Not used)
## Prerequisites
1. To run this notebook/code you need to clone the repo and install python 3.10.2 either in your base environment or virtual/conda environment.
2. Run below command in your environment to install the libraries required:

```
pip install -r requirements.txt
```
3. To run the notebook you also need jupyter notebook installed.
## License
Distributed under the MIT License. See LICENSE.txt for more information.
## Acknowledgement
The analysis wouldn't have been possible without the open source data shared on kaggle ([Seattle-Airbnb-data](https://www.kaggle.com/datasets/airbnb/seattle)).
