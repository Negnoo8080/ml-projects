# Project 6: Deploying a Machine Learning Model as a Flask API

## What this project does
In this project, we learned how to turn a Python machine learning script into a local web service. We wrapped the diamond carat classification model from previous exercises inside a Flask app.

## What I did:
* Set up a local web server using the **Flask** framework.
* Created a **GET** endpoint (`/diamond/sample`) that returns a sample data entry in JSON format.
* Created a **POST** endpoint (`/diamond/evaluate`) that accepts custom JSON data from a user, converts it into a Pandas DataFrame, runs it through our trained KNN model, and returns the predicted range.
* Added a basic check to make sure the incoming request is in the correct JSON format.

## Libraries used:
* Flask
* Scikit-Learn
* Pandas & NumPy
