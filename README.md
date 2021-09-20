# IPL-First-Innings-Score-Prediction
### https://ipl-scores-prediction.herokuapp.com/<br>
IPL First innings score predictor, a machine learning web app created with Flask on Heroku platform.

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#Technical-Aspect)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Technologies used](#technologies-used)
  * [Bug / Feature Request](#bug---feature-request)
  * [Future scope of project](#future-scope)
  * [Credits](#credits)

## Overview
This is a flask web app which predicts the first inning score of Indian Premier League(IPL) with the help of Rgeressor model. The dataset is taken from https://github.com/codophobia/CricketScorePredictor 

## Technical Aspect:
This project is divided into two parts:
1) Trained a Machine Learning model using Regressor Models(Code is available in this repo).
2) Deployed the model using Flask on Heroku Platform.

## Directory Tree 
```
├── static 
│   ├── styles.css
├── template
│   ├── index.html
|   ├── reult.html
├── IPL Score Prediction.ipynb
├── Procfile	
├── README.md
├── app.py
├── ipl.csv	
├── ipl_score_prediction1.pkl
├── requirements.txt
├── runtime.txt
```

## Technologies used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) [<img target="_blank" src="https://i.imgur.com/gh8nX4U.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/)

## Future Scope
• Consider venue as one of the aspect while creating a model.
• Add columns of the striker and non striker batsman who is playing at that moment.
• Implement this problem statement using Deep Learning(ANN).

## Credits
* Dataset: The dataset contains the score made on each ball of the matches played in IPL from 2008 to 2017.
* Dataset Link: https://github.com/codophobia/CricketScorePredictor (Credits to Shivam Mitra)
* Web App: https://ipl-scores-prediction.herokuapp.com/


