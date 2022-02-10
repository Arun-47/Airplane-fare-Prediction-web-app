
## AIRPLANE FARE PREDICTION

### DEMO
Web app link: https://airplane-fare-predictor.herokuapp.com/

![App Screenshot](https://i.imgur.com/LzrNFpR.png)

![App Screenshot](https://i.imgur.com/lTGIAtn.png)


### OVERVIEW
Web appication that predicts the flight fare of an airplane travel in india. 
built using Flask for building application and sklearn was used to 
implement machine learning model (SVR) to predict. The site was hosted on Heroku. 

### REQUIREMENTS
The Code was written in Python 3.9.1. 
To install the required packages and libraries, run this command in the project directory after cloning the repository:
```bash
pip install -r requirements.txt
```
### DIRECTORY TREE
```bash
│   app.py
│   FARE DATA.xlsx
│   Procfile.txt
│   requirements.txt
│   runtime.txt.txt
│   SVR MODEL.ipynb
│
├───PKL FILES
│       fare_model.pkl
│       feature_scale_model.pkl
│       X_feature_scale_model.pkl
│
├───static
│   ├───css
│   │       Home.css
│   │       nicepage.css
│   │
│   ├───images
│   │       4353032.png
│   │       min.jpg
│   │
│   └───js
│           jquery.js
│           nicepage.js
│
└───templates
        Home.html
        index.html
```
## Future Scope

* Improve the ML algorithm
* Optimize web app features
* Improving UI design

### 🔗REFERECES
 - [Data set used](https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh)
 - [Heroku](https://dashboard.heroku.com/apps)
 - [Project](https://github.com/Mandal-21/Flight-Price-Prediction)


