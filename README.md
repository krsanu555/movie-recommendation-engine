# Recommendation Engine

The objective of this project is to recommend movies to the user based on
 1. favourite aspects of an item drawn from the previously watched movies.
 2. similarity of the other users that have similar preferences and opinions to this user.

### Project description
For this, we have used two approach
 1. [Content Based Recommendation System](https://github.com/krsanu555/movie-recommendation-engine/blob/master/Content-Based-movies.ipynb)
 2. [Collaborative Filteing Recommendation System](https://github.com/krsanu555/movie-recommendation-engine/blob/master/Collaborative-Filtering-movies.ipynb)

### Set up
1. Clone the repository
```
git clone https://github.com/krsanu555/movie-recommendation-engine.git
```
2. Move inside the newly created repository
```
cd movie-recommendation-engine
```
3. Create a virtual environment and activate it (optional)
```
python3 -m venv env
source env/bin/activate
```
4. Install all libraries
```
pip install -r requirements.txt
```
5. Start jupyter
```
jupyter notebook
```
6. Run jupyter files you want
  - Content-Based-movies.ipynb
  - Collaborative-Filtering-movies.ipynb  
  
7. Deactivate environment (if created and activated before)
```
deactivate
```
