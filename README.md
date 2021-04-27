# Employee-transport-management-system 🚗✔

## Table of Contents
  * [About the project](#about-the-project)
  * [Installation](#installation)
  * [About the dataset](#about-the-dataset)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Technologies used](#technologies-used)

## About the project
In this project the employee of a comapany will be able to login to companies transport service website able to book cabs and apply for leave.
An SMS will be sent to the user confirming that the cab is booked and Leave application is sent.

## Installation
First create an account at [Vonage.com](https://dashboard.nexmo.com/sign-up) \
Get the API Key ad API Secret Key from the [Dashboard](https://dashboard.nexmo.com/) of the website.\
Now clone the following repository :\
https://github.com/Rakesh-Naidu/employee-transport-management-system-login-page \
Now in the project directory create an ``.env file`` and store the API Key and API Secret Key with the variable names shown below.
/////////////////////////////////////////\
In the project directory, run the following commands
### ```npm install```
This command installs all the dependencies required for this project.
### ```npm start```
This command runs the app in localhost. \
It prints ``listening at 3000`` to confirm that.\
Keep the app running.
## About the dataset
This dataset was derived from the 1990 U.S. census, using one row per census block group. A block group is the smallest geographical unit for which the U.S Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

## Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```
├── static 
│   ├── css
|   |   ├── cssfile.css
|   |   ├── h3.jpg
├── template
│   ├── index.html
├── Procfile
├── README.md
├── app.py
├── Housing_Price_EDA.ipynb
├── Housing_Model.ipynb
├── model.pkl
├── housing.csv
├── requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 
