# Movie-Recommendation-Systems
An exploratory analysis on movie database and development of movie recommendation systems.

This notebook used a movie database from https://www.kaggle.com/rounakbanik/the-movies-dataset. The first part of the notebook provides an exploratory analysis of the dataset to get some insights. There are also some exploratory questions that we think worth to look for. 

The second part of the notebook provides the development of a recommendation system (i would say this is a traditional recommendation syatem) than uses content information. The content used are the description of the movies, the cast and crew information toogether with keywords used for the movie. The content processing for this system mainly uses the typical natural langguage processing pre-processing such as tokenization and stemming. The term frequency inverse document frequency matrix normally used for text retrieval is derived and the cosine similarity is used to compute the similarity between the vector in the matrix.

The third and final part of the notebook are the development of the collaborative filtering and hybrid recommendation systems. The former make used of the viewer ratings informations as the source of information for new movie recommendations. The surprise library that consist of SVD algorithm approach is employed recommend new movie based on user's previous movie ratings. And finally the hybrid recommendation system combined together the content based and collaborative based approach to fully personalised movie recommendation.

