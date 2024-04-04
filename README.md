# Twitoff
This code is a Flask application called TwitOff, which provides a web interface for comparing and predicting which Twitter user is more likely to have written a given tweet.
It utilizes the Twitter API, the spaCy natural language processing library, and a logistic regression model for prediction.

## Development
The code is organized into several files:

* app.py: Main Flask application file that handles routes and views.
* models.py: Defines the database models for users and tweets using SQLAlchemy.
* predict.py: Contains the logic for predicting which user wrote a given tweet using a logistic regression model.
* twitter.py: Contains functions for interacting with the Twitter API, adding or updating users and tweets in the database, and vectorizing tweets using spaCy.
