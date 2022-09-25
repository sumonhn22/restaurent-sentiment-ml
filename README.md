# End to End ML implementation of Restaurant Review's Sentiment Analysis 

### Steps that one needs to be implemented:

Step 1. Push into github: create git repository in same name by adding README file, .gitignore in python, Apache License 2.0 
        clone the folder in local directory: ``` git clone ....... ```

Step 2. Open the dir in VS code for ML implementation:
        Preparing dataset and finalize model trianing, Save model in pkl file

Step 3. Create new env: ``` conda create -p venv python==3.7 --y ``` and 
          ``` conda activate ......  ```
          
Step 4. Create requirement file, run essential package:  ``` pip install -r requirements.txt ```

### Push into Github
```
git add .
git commit -m " massage "
git push origin main
```
Step 5. Create home.html file in template folder for front end 

Step 6. Create ``` app.py ``` for Flask web application 
        Cheack the apps in localhost so run: ``` python app.py ```

### Deploy in Heroku 
1. Create Procfile by adding :   ``` web: gunicorn app:app  ```
2. Deploy the apps in Heroku by pushing latest file into github

### Automation CI/CD pipeline

1. Create Dockerfile with essential steps 
    
2. Create folder: ``` .github/workflows ``` and make ``` main.yaml ``` file in it which is available in google
     
### Set up Github Actions;  
  1. In github:  Go setting/Secrete/Actions   
  2. Create new secret as follows: 
            HEROKU_API_KEY, Value: pick API key from heroku account setting 
            HEROKU_EMAIL,   Value: email for heroku
            HEROKU_APP_NAME,  value: app name form heroku

-- Finally, push all changes in github and Go your app in heroku app.










<!--  ![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![NLTK](https://img.shields.io/badge/Library-NLTK-orange.svg)

• This repository consists of files required to deploy a ___Machine Learning Web App___ created with ___Flask___ on ___Heroku___ platform.

• If you want to view the deployed model, click on the following link:<br />
Deployed at: _https://restaurant-reviews-sentiment.herokuapp.com/_ -->

<!-- • If you are searching for __Code__, __Algorithms used__ and __Accuracy__ of the model.. you won't find it here. Click the link mentioned below for the same:<br />
Link: _https://github.com/anujvyas/Natural-Language-Processing-Projects/tree/master/Sentiment%20Analysis%20-%20Restaurant%20Reviews_

• Please do ⭐ the repository, if it helped you in anyway.

• A glimpse of the web app:

![GIF](readme_resources/restaurant-review-web-app.gif)

_**----- Important Note -----**_<br />
• If you encounter this webapp as shown in the picture given below, it is occuring just because **free dynos for this particular month provided by Heroku have been completely used.** _You can access the webpage on 1st of the next month._<br />
• Sorry for the inconvenience.

![Heroku-Error](readme_resources/application-error-heroku.png) -->
