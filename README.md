# movielens-data-exploration

This focus of this project is employ exploratory analysis of movielens dataset(https://grouplens.org/datasets/movielens/1m/) inorder to get interesting insights.
The dataset contains 3 related data sources: ratings, users and movies in .dat format.
- ratings.dat contains attributes UserID, MovieID, Rating and Timestamp reprenting id of user, id of movie, rating given by user to the movie and timestamp of the rating.
- users.dat contains attributes UserID, Gender, Age, Occupation and Zip-code for each user.
- movies.dat contain attributes MovieID, Title and Genres.

### Phase of analysis:
- Explore each data sources individually.
- Combine movies and users to the ratings data inorder to get interesting insights.

###  Libraries
- Pandas: for data manipulation and analysis. Dataframe feature provided by this library is really flexible in handling the data.
- Numpy: provide flexibility in dealing with multi-dimensional arrays and complex mathematical functions.
- Matplotlib: Commonly used library for data visualization
- Searborn: visualization library based on matplotlib. It provides high-level interface to attractive graphs.
Run command: <code>pip install -r requirements.txt</code> to install required libraries.

### To run the code
Common requirements: Python 3+(version used for the project: 3.5.3), Jupyter notebook

Data directory: /src/main/data(data needs to be downloaded from https://grouplens.org/datasets/movielens/1m/)
Extract the zip and copy ratings.dat, users.dat and movies.dat to this directory.

code directory: /src/main/code
code file: exploratory_analysis.ipynb(jupyter notebook)
Run each cell of the jupyter in the order.
