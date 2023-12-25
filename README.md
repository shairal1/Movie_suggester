# Movie Recommender System

This movie recommender system is designed to provide personalized movie recommendations based on IMDb data. The system utilizes cosine similarities calculated from various features, including reviews, actors, genres, etc., to suggest movies similar to the user's preferences.

## Demo

Check out the live demo of the Movie Recommender System deployed on Streamlit: [Demo Link](https://movie-suggester-z0mk.onrender.com)

**Note:** The demo may experience some slowness due to the use of a free version of Streamlit on Render. Please be patient.

## How It Works

1. **Select Your Favorite Movie:**
   - Use the drop-down menu to choose your favorite movie from the IMDb dataset.

2. **Get Similar Movie Recommendations:**
   - The system calculates cosine similarities based on various movie features.
   - It then displays movie posters of similar movies in the order of relevance.

## Deployment

The movie recommender system is deployed using Streamlit on Render.
## File Structure

- **`app.py`**: Main Streamlit application file.
- **`data/`**: Folder containing the preprocessed IMDb data.
- **`models/`**: Folder with scripts for calculating cosine similarities.
- **`requirements.txt`**: List of Python dependencies.

## Data Preprocessing

The IMDb data is preprocessed to extract relevant features for creating cosine similarities. This includes reviews, actors, genres, and other relevant information.

## Acknowledgments

The recommender system is built upon the insights from the IMDb dataset and utilizes [libraries/frameworks used for data preprocessing, similarity calculation, etc.].


