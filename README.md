# Bollywood-movie-recomendation-system
content based recommendation engine

link for heroku app live demonstartion:https://bollywoodmovie-recomendation.herokuapp.com/
link for imdbpy:https://buildmedia.readthedocs.org/media/pdf/imdbpy/stable/imdbpy.pdf


The  model waas on  Content Based Recommendations to find similar movies. Intuitive idea behind is "If a person likes a particular item, he/she will also like an item that is similar to it." The dataset is prepared by me from colletcing data from various sources using buitiful soup and tmdbapi

used  imdbpy for extracting information like genre,directorname one cn refer above link 

collected data from wikipedia using webscarpping i uploaded all files in preprocessing folder

Similarity Score :
How does it decide which item is most similar to the item user likes? Here we use the similarity scores.

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

How Cosine Similarity works?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

picture representaion:https://user-images.githubusercontent.com/36665975/70401457-a7530680-1a55-11ea-9158-97d4e8515ca4.png
