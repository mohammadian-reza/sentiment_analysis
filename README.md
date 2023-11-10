<img align="left" hspace="100" alt="Coding" width="400" src="https://cdn.dribbble.com/users/247769/screenshots/6193788/media/ef684d0bf94d33a70251db49da02301e.gif">

<img align="right" alt="Coding" width="400" src="https://cdn.dribbble.com/users/954572/screenshots/16765270/media/9265ca52c0278b81ce7e656f8f3356ce.gif">

<img alt="Youtube" align="left" hspace="100"  height= "200" width="250" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZ2JwY2Nvajd0ZGo4bDVmZzl6b3p0MDgwYWpiam93cTMyMW5tcm4zNCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/13Nc3xlO1kGg3S/giphy.gif"  >
<img alt="comment" hspace="400" height= "200" width="250" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExamM5cGtyYjRrZHF3ZXV0b3JrbWxvNGI0YWU4dXVtbm90bzFqb2VydSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/hbwUaes8G8b17sPg9R/giphy.gif">
________________________________________________________________________________________________________________________________________________________

# Sentiment_analysis
### This repo contains sentiment analysis based on comments and rates on YouTube and Amazon platforms.


# **1. Amazon Food rate**  

##### :red_circle: **You could download the dataset with this command: ``` ! kaggle datasets download -d snap/amazon-fine-food-reviews  ```**

###  Employing Sentiment analysis using 2 different techniques

#### 1. VADER (Valence Aware Dictionary and Sentiment Reasoner)
#### 2. Roberta pre-trained Model
#### 3. Huggingface Pipeline

* ### Step 1.1. VADER Sentiment Scoring

    * #### We will use NLTK's **SentimentIntensityAnalyzer** to get the neg/neu/pos scores of the text.

    * #### This uses a "bag of words" approach:
> 1. Stop words are removed
> 2. Each word is scored and combined to a total score.

* ### Step 2. Roberta Pre-trained Model:
> 1. Use a model trained on a large corpus of data
> 2. Transformer model accounts for the words but also the context related to other works

* ### Step3: Compare Scores between models

* ### Step 4: Review Examples:
    * Positive 1-Star and negative 5-Star Reviews
* ### Step 5: The Transformers Pipeline
    * Quick and easy way to run sentiment predictions
 

# **2. The YouTube comments Sentiment Analysis**
##### :red_circle: **You could download the dataset with this command: ``` ! kaggle datasets download -d datasnaek/youtube-new ```**
##### :red_circle: **You could download the dataset with this command: ``` ! kaggle datasets download -d datasnaek/youtube ```**
  * find correlations between likes and comments
  * investigate the distribution of negative and positive comments

    * ### Step 1: Import all the necessary packages!
    * ### Step 2: Perform Sentiment Analysis
    * ### Step 3: Wordcloud Analysis of your data
    * ### Step 4: Perform Emoji's Analysis
    * ### Step 5: Collect the Entire data of Youtube!
    * ### Step 6: Export data into (CSV, JSON, DB)
    * ### Step 7: Which Category has the maximum likes?
    * ### Step 8: Find out whether the audience is engaged or not
    * ### Step 9: Which channels have the largest number of trending videos?
