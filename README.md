# NLP1

## Deployment

#### 1.Create the bin directory 

Add a bin folder in the root of your local project

#### 2.Add installation packages in the bin directory

- post compile 
- install_nltk_data

#### 3.Commit all of the files to github repo

#### 4.use Heroku to deploy app

- login to heroku 
- connect to the github repository
- add the nltk_data file to the local project repo
- Set the NLTK_DATA environment variable on your heroku app: **heroku config:set NLTK_DATA='./nltk_data' --app appnlp**
- deploy the **master** branch 
