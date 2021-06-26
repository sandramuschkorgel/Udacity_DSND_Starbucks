# A Starbucks Customer Loyalty Program Analysis
Although Starbucks is anchored in the United States, the brand is popular around the globe. To further increase customer engagement with the brand, Starbucks has implemented a loyalty rewards program. The goal is to recommend something the customer likes and eventually buys, saving them money while increasing Starbucks' revenue.

## Description
This report summarizes my efforts to create a recommendation system for members of the Starbucks loyalty program. Based on a given user identification, the recommender returns one or more offers which are predicted to receive positive feedback, ultimately increasing customer retention. The data was provided by Starbucks through Udacity. However, all entries are fictitious and do not represent real customers. 

The GitHub repository is structured as follows:
* 1 main jupyter notebook *Udacity_DSND_Starbucks.ipynb*: Here you will find the entire CRISP-DM.
* 3 json files containing the original data
  * *profile.json* is a user database that stores information about age, gender, income and the date when a user became a member.
  * *portfolio.json* lists all available offers a user might have received and specifies the type of offer, the offer period, the associated reward, the channels through which the offer was sent to users, and the offer difficulty, which is the upfront investment a user must make to receive a reward.
  * *transcript.json* contains event data over a two-year period, logging the following events: receiving an offer, viewing an offer, completing an offer, and spending the amount x on a purchase that might or might not be associated with an offer.

## Dependencies/Pre-requisites
In order to run this project install the following packages
* [NumPy](https://numpy.org/install/) and [pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
* [matplotlib](https://matplotlib.org/stable/users/installing.html) and [seaborn](https://seaborn.pydata.org/installing.html)  
* [scikit learn](https://scikit-learn.org/stable/install.html)

## Installation and Usage
```bash
git clone https://github.com/sandramuschkorgel/Udacity_DSND_Starbucks.git
cd [project root directory]
run jupyter notebook
```

## Read more
[Click here for my substack blog post](https://sandramuschkorgel.substack.com/p/making-offers-customers-like)

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Acknowledgments
This project is part of the Udacity [Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025). Thanks to [Starbucks](https://www.starbucks.com/) for providing the original datasets.
