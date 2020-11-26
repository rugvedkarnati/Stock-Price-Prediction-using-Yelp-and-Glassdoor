<h1>Stock Price Prediction using Yelp and Glassdoor</h1>

Authors: Tanmay Gatle, Rugved Sai Karnati, Sanat Batra

Python 2.7 is required.
Run the run.py file to get the results

Company names - 'Macys', 'McDonalds', 'Apple', 'Nike', 'HomeDepot', 'Gap'.
McDonalds_prediction_plot_only_stock.png is the plot of the prediction for McDonalds stock price 9 periods (27 months into the future) using only its past stock price values.
McDonalds_prediction_plot.png is the plot of the prediction for McDonalds stock price 9 periods (27 months into the future) using its past stock price values, number of yelp 5 star reviews and number of glassdoor 5 star reviews.

To change the features used, change line 1121 from features = ['stock', 'glass_5', 'yelp_5'] to features = ['stock'], to use only past stock data.

yelp_scraper.py - Used to scrape Yelp for customer ratings.
glassdoor_scraper.py - Used to scrape Glassdoor for employee ratings.
