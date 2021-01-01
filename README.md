# Recommendation-engine-with-IBM
### Table of Contents

1. [Summary](summary)
2. [Installation](installation)
3. [File Descriptions](File_Descriptions)
5. [Data](Data)
6.[Project Overview](Project_Overview)
6. [Acknowledgements](Acknowledgement)

## Summary:
This project and the associated code are meant to serve as an assignment project for the partial fulfilment of the Udacity Data Scientist Nanodegree.his project was designed to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles.
The project contains the following tasks:
- Exploratory Data Analysis: This part is for data exploration.
- Rank Based Recommendations: To get started in building recommendations, I first find the most popular articles based on the most interactions. These are then the articles we might recommend to new users (or anyone depending on what we know about them).
- User-User Based Collaborative Filtering: In order to build better recommendations for the users of IBM's platform, I look at users that are similar in terms of the items they have interacted with. These items could then be recommended to similar users.
- Content Based Recommendations:  Using  NLP skills, I developed a content-based recommendation system.
- Matrix Factorization: Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, I built out a matrix decomposition. Using the decomposition, I got an idea of how well I can predict new articles an individual might interact with .    


##  Installations
This project requires Python 3.x and the following Python libraries installed:
- [Nltk](https://www.nltk.org/)
- [Pandas](http://pandas.pydata.org)
- [Progressbar](https://pypi.org/project/progressbar/)
- [Seaborn](https://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

## File Descriptions

File<a name="File"></a> : Recommendations_with_IBM.ipynb


## Data
- user-item-interactions.csv: file contains user interaction.
- articles_community.csv: file contains articles description.  

## Project Overview

I. Exploratory Data Analysis

Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

II. Rank Based Recommendations

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

IV. Content Based Recommendations

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

V. Matrix Factorization

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.



## Acknowledgments
I would like to thank [Udacity](https://eu.udacity.com/) for this amazing project, and [IBM](https://dataplatform.cloud.ibm.com/) for providing the data.
