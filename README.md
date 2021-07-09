# IPL-Score-Prediction

## Overview
This is a Flask web app which predicts scores of first innings in IPL matches.




## Installation
The Code is written in Python 3.8 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```


## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download Hroku CLI to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```
├──Static
├── templates
│   ├── index.html
    ├── result.html
├── Procfile
├── README.md
├── app.py
├── IPL model.ipynb
├── first-innings-score-lr-model.pkl
├── requirements.txt
```

## Frontend Using Flask and HTML

https://iplpredx.herokuapp.com/predict

![image](https://user-images.githubusercontent.com/75041273/125139977-2aa37500-e12f-11eb-9f97-0dc5da69e7f8.png)

![image](https://user-images.githubusercontent.com/75041273/125140079-5d4d6d80-e12f-11eb-86f5-6298b886fdcd.png)

![image](https://user-images.githubusercontent.com/75041273/125140057-5161ab80-e12f-11eb-8f33-d5849a3cc225.png)





## 🏁 Technology Stack

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 

## 📋 Further Changes to be Done

- [ ] Deploying the Web Application on Cloud.
     - [ ] Google Cloud 
     - [ ] Azure
     - [ ] AWS EC2 Instance
 
 
