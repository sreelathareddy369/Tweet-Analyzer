# Tweet-Analyzer
Web App Link : https://tweet-analyzer.herokuapp.com/

This is a cool web app integrated with twitter which takes the twitter handel as as input and does :

1.Analyze the tweets of your favourite Personalities

This tool performs the following tasks :

Fetches the 5 most recent tweets from the given twitter handel
Generates a Word Cloud
Performs Sentiment Analysis a displays it in form of a Bar Graph
2.This tool fetches the last 100 tweets from the twitter handel & Performs the following tasks Converts it into a DataFrame

Cleans the text

Analyzes Subjectivity of tweets and adds an additional column for it
Analyzes Polarity of tweets and adds an additional column for it
Analyzes Sentiments of tweets and adds an additional column for it
This respository contains all the files for end to end model building and deployment of tweet analyzer web app

Procfile : To generate command to run the app

Tweet_Analyzer.ipynb : Model building File

Twitter Data : File created after every query on the web app

Requirements.txt: Requirement file

setup.sh : predefined file for streamlite on heroku

This app is created on a tool called Streamlit which saves you from the headache of front-end devlopment ,you can install it by: Streamlit documentation: https://docs.streamlit.io/en/latest/

pip install streamlit

& to run it on local host : streamlit run myfile.py

