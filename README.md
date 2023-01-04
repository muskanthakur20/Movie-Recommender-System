# Movie-Recommender-System
A content-based recommender system that recommends movies similar to the movie the user likes.
The main parameters that are considered for the recommendations are the genre, director and top 3 casts. The details of the movies, such as title, genre, runtime, rating, poster, casts, etc. are fetched from TMDB.
## Dataset link:
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv
## Libraries used:
Numpy, Pandas, Scikit-learn, Nltk and Pickle
## How to get the API key?
Create an account on https://www.themoviedb.org/ . Once you successfully created an account, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for an API key. 
If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request has been approved.
## How Cosine Similarity works?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. 
The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

![Cosine](https://user-images.githubusercontent.com/118469585/210548016-58e46362-0e5a-4d5d-bef0-715715b475ff.png)
## How to run the project?
1. Open the .pynb file in Google Colab and Upload the datasets in it.
2. When Pickle library will run it will create three new .pkl files, download these files
3. Run the app.py file in PyCharm Software
4. Install the required Libraries
5. Run it in terminal
6. Hurray! That's it.
### It will look like this
![Screenshot (5)](https://user-images.githubusercontent.com/118469585/210548622-ed20dd06-136f-4f9d-a56b-64cba9b47202.png)


