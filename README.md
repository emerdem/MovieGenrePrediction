# Advanced Topics in Data Science - Predicting Movie Genre using Machine Learning and Deep Learning

The aim of this project was to predict movies genres from a number of attributes of movies. The data we used were randomly extracted from IMDB and TMDB movie databases through APIs. We merged the two data sets using IMDB IDs and obtained 4444 movies including the following features, classified in the following groups:

Meta features: budget, original language, popularity, production company, production country, release data, revenue, runtime, spoken language, vote average, vote count, 
Director, actors, writer
Text features: overview, title, tagline
Image features: poster images (pixels) 

In the beginning, we computed the correlation between the genres as well as part of meta features and the results showed that there is very little correlation between genres. Also even though some metadata features might be useful in our prediction such as production company, production country and voting average, overall there is weak correlation with genre. Therefore our prediction accuracy would be low if we only use metadata from TMDB and IMDB. In addition to the metadata that have correlation over 3% with genre, we incorporated image recognition of posters and natural language processing of plot summaries / actors, writer and directors to help us improve our accuracy.
