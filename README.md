# Sentiment Classifier

This repository represents the core application used for a Cloud Computing's course project.


The web app is designed to run a underlying sentiment classifier model trained by the means of a `PyTorch` CNN that will allow users to evaluate random brands by writing reviews. While writing, the user will see the sentiment score of his input updating in real-time.

The user can then change the rating in case the suggested one does not reflect his views, and submit.

The data used has been scraped from a customer review website using `Selenium` and `Scrapy`.

The user interface of the web app is build using `Dash`. 

Also a `REST API` and a `Postgres` database has been set for the backend.

Finally the app has been dockerized using `Docker Compose` and then deployed to `AWS`.



