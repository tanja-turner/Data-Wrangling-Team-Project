# Data-Wrangling-Team-Project
Python data wrangling project

1.0 Objective and Problem Statements

In real life, data scientists and analysts are almost never given a clean dataset that they can just plug into their analysis. Reasons for this are many, most important being that data is seldomly collected for the purpose of doing data analysis on it. It is usually collected as part of the normal business processes and often across multiple systems. Therefore, before we, as data analysts, can attempt to analyse the data, we need to bring it to a usable form, cleaned and optimized for the purpose we need it for. Hence, the term data wrangling. We need to wrangle with it until we can get it in the format that we want it in.

The objective of this project was just that - to find a dataset to answer some question or use in machine learning models and to wrangle with it until we bring it into a shape and form where it can be used to answer the question or make a prediction.

Some of the questions that can be answered with this dataset are as follows:

What is the most popular genre
What are the top studios based on number of released movies or gross eranings
Which actors/actresses produced most movies
Are there any trends in the number of movies produced per year
Are there any months when more movies are released than usual
What are the top 10 movies based on income/ popular vote
Which directors produce movies with highest income
The datasets can also be used for model building, although we did not do it. Some of the predictions that can be built is which movie would win and Oskar, how much profit a movie would make etc.

2.0 Datasets and Background

A dataset consisting of 4 csv files was selected from Kaggle at https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset The movies dataset includes 85,855 movies with attributes such as movie description, average rating, number of votes, genre, etc. The names dataset includes 297,705 cast members with personal attributes such as birth details, death details, height, spouses, children, etc. The ratings dataset includes 85,855 rating details from demographic perspective. The title principals dataset includes 835,513 cast members roles in movies. The complete description of variables retained after file manipulation is provided further down in the notebook.

In addition, Rotten Tomatoes movie ratings were obtained from Kaggle at https://www.kaggle.com/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset and financial data was scraped from the web at https://www.boxofficemojo.com/year/world/?ref_=bo_nb_hm_tab

Due to the large size of files and lesser availability of data for older movies, it was decided to filter all datasets and only retain movies with a release date between 2000 and 2019.
