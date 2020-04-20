# Python_Project_Movies
Using popular data wrangling, visualization and machine learning techniques to clean, merge and analyse the movies data from IMDB(scraped from web) and Wikipedia(from Kaggle). 

# Collaborators

Himaja Gaddam </br>
Venkat Sureddi

# Data Loading

We have taken data from two sources i.e IMDB website and Kaggle Wikipedia Movies Dataset (https://www.kaggle.com/jrobischon/wikipedia-movie-plots). The data from IMDB website was obtained through web scraping.

# Packages Used For Our Analysis

•	bs4 </br>
•	pandas </br>
•	numpy </br>
•	requests </br>
•	randint </br>
•	warnings </br>
•	nltk </br>
•	matplotlib </br>
•	seaborn </br>
•	plotly </br>
•	sklearn </br>
•	sys </br>
•	os </br>
•	wordcloud

# Data Wrangling

We've identified the columns required for the exploration and analysis of data from both datasets. Then, we removed the duplicates from both datasets. Title column is common for both datasets and hence to join these two datasets on title we converted the title column to lowercase. Then, we clubbed both the datasets on the Title column. </br>

Since the movies have multiple genres associated with them, we use dummy variables for genres so that model building becomes easy.

# Exploratory Data Analysis

We first clean up the plot column by removing the punctuations and stopwords. We then create a wordcloud from the words which are being repeated multiple times. </br>


In addition to this, we also see: </br>
•	The trend of metascore rating and IMDB rating across the years and across genres </br>
•	The number of movies across each genre per year </br>
•	Comparison of metascore rating and IMDB rating across genres (clustered using metascore key) </br>

# Data Modelling

For our text analysis, we split the data into test and training and applied the following the models:

•	SVC </br>
•	MultinomialNB </br>
•	Logistic Regression </br>
•	K Neighbors Classifier </br>
•	Decision Tree Classifier </br>
•	Random Forest Classifier </br>
•	AdaBoostClassifier </br>
•	BaggingClassifier </br>
•	ExtraTreesClassifier </br>
