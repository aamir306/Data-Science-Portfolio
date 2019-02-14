# Data Science Portfolio
Repository containing portfolio of data science projects completed by me for self learning. Presented in the form of jupyter Notebooks.

*Note: Data used in the projects (accessed under data directory) is for demonstration purposes only.*

## Contents
- ### Data-Cleaning-Airbnb([Notebook](https://github.com/llAamirll/Data-Science-Portfolio/blob/master/Data-Cleaning-Airbnb/Data_Cleaning_Notebook.ipynb))



*Tools:* 
- ### Loan-Prediction([Notebook](https://github.com/llAamirll/Data-Science-Portfolio/blob/master/Loan-Prediction-/loan%20prediction%20random%20forrest.ipynb)) 
This project contains data about loan applicants as features and their loan status as target variable.The random forrest classifier is used with 80% accuracy.
steps-
1. Getting Libraries and data
2. exploratory data analysis
3. Filing the Missing values
4. preprocessoring - hot encoding 
5. Random forrest model building
6. Tunning the parameters

*Tools:seaborn ,matplotlib,missingno ,numpy,warnings,LabelEncoder,RandomForestClassifier*



- ### Movie-Recommandation-system ([Notebook part1](https://github.com/llAamirll/Data-Science-Portfolio/blob/master/Movie-Recommandation-system/1.Cleaning_recom_system.ipynb)-[Notebook part2](https://github.com/llAamirll/Data-Science-Portfolio/blob/master/Movie-Recommandation-system/2.Final_recom_system.ipynb))
This project consist of 5000 movies imdb dateset in which their actor ,dircetor name ,genre plot and regarding imformation is given.
Movie recommendation system is created by cosine similarity .The whole project breaken down into two parts
1.Data cleaning 2.Recommandation System

*Tools:cosine_similarity,CountVectorizer, pandas,numpy,missingno,seaborn*


- ### Time-series-Analysis([Notebook](https://github.com/llAamirll/Data-Science-Portfolio/blob/master/Time-series-Analysis/Time%20series.ipynb))
 Forecasting is the process of estimating future sales. Data Time series analysis applied on Superstore's Sales data.
Steps -
1. Importing useful libraries
2. Geting data and  drop the unncessary columns
3. Visualizing the series
4. Test for Stationarity
5. Decomposing
6. plot ACF/PACF and Find Optimal Parameters
7. Build ARIMA Model

*Tools:statistics ,statsmodels,pandas,numpy ,matplotlib*


- ### Web-Sracaping-of-internshala([Notebook](https://github.com/llAamirll/Data-Science-Portfolio/blob/master/Web-Sracaping-of-internshala/Web%20Scraping%20.ipynb))
This project web scrap all the posts of data science internship in nice tabular form.

*Tools:requests,BeautifulSoup,pandas*


- ### Demonetisation_sentiment_analysis([Notebook](https://github.com/llAamirll/Data-Science-Portfolio/blob/master/demonetisation_sentiment_analysis/Demonetisation_Sentiment_Analysis.ipynb))
The Government of India announced the demonetisation of all ₹500 and ₹1000 banknotes.kaggle dataset of tweets during demonetisation is used to analysis sentiments.
Steps-
1.Importing libraries and data
2.cleaning data
3.Label Each tweet as either positive review or negative.
4.Plot sentiment graph
5.Wordcloud of sentiment

*Tools:BeautifulSoup,plotly,nltk,wordcloud,matplotlib*


- ### CNN-Facial-recognition-keras([Notebook part1](https://github.com/llAamirll/Data-Science-Portfolio/blob/master/CNN-Facial-recognition-keras/Preprocessing_CNN_Indian_Actors_Face_Recognition.ipynb)-[Notebook part2](https://github.com/llAamirll/Data-Science-Portfolio/blob/master/CNN-Facial-recognition-keras/Facial_recognition_keras.ipynb))
 Indian Actors Face Recognition is kaggle dataset .The dataset includes images of 5 famous Indian film stars. The dataset has been made smaller .The .zip files contain 5 directories and each of them has 30 images of actors.The second zip file contains validation images so that we can evaluate your model.

Steps : This project divided into two parts-
part1
Getting libraries
Renaming the filenames and save to one place
Save filename with their corresponding label in pandas

part2
Importing libaries and label file
Creating functions for image manipulation
Prepare the data to feed into model
Buliding the model
Train the Model
Test image on new images

Tools - numpy ,pandas,tqdm, cv2 , dlib ,matplotlib,keras,ImageDataGenerator


If you liked what you saw, want to have a chat with me about the portfolio, work opportunities, or collaboration, shoot an email at aamir.k306@yahoo.com
