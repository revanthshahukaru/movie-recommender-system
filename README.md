# Movie Recommender System

This repository contains the code for a comprehensive Movie Recommender System. The system utilizes multiple recommendation techniques including content-based filtering, collaborative-based filtering, popularity-based filtering, and hybrid filtering to provide personalized movie recommendations. The final model leverages content-based filtering, integrating genre, cast, crew, and keywords to enhance the accuracy and relevance of recommendations.

## Project Overview

The Movie Recommender System was developed to help users discover new movies based on their preferences. By inputting a movie they like, users can receive recommendations for similar movies, filtered by genre and rating. This project handles a dataset of over 47,000 data points and 35 features, ensuring a rich and diverse recommendation set.

## Features

- **Content-Based Filtering**: Recommends movies based on the similarity of content (genre, cast, crew, keywords) with the user's preferred movie.
- **Collaborative-Based Filtering**: Utilizes user interaction data to recommend movies enjoyed by similar users.
- **Popularity-Based Filtering**: Suggests movies based on overall popularity and ratings.
- **Hybrid Filtering**: Combines multiple filtering techniques to improve recommendation quality.

## Web Application

The system is deployed as a user-friendly web application using Streamlit. Users can input their favorite movie, select a genre, and set a minimum rating to receive tailored recommendations. The application fetches movie posters using the TMDB API to enhance the visual appeal.

## Key Technologies

- **Python**: Main programming language for data processing and model implementation.
- **Pandas & Numpy**: Data manipulation and numerical operations.
- **Scikit-learn**: Machine learning library for implementing filtering techniques and similarity measures.
- **Streamlit**: Framework for building the web application.
- **TMDB API**: Fetches movie posters to display alongside recommendations.
Here's an updated "How to Run" section with instructions for both macOS and Windows users:

## How to Run

### macOS Users

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/movie-recommender-system.git
    cd movie-recommender-system
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app**:
    ```bash
    streamlit run app.py
    ```

5. **Interact with the application**:
    Open your web browser and go to `http://localhost:8501`. Input your favorite movie, select a genre, and set a minimum rating to get recommendations.

### Windows Users

1. **Clone the repository**:
    ```bash
    git clone https://github.com/revanthshahukaru/movie-recommender-system.git
    cd movie-recommender-system
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

3. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app**:
    ```bash
    streamlit run app.py
    ```

5. **Interact with the application**:
    Open your web browser and go to `http://localhost:8501`. Input your favorite movie, select a genre, and set a minimum rating to get recommendations.

## Dataset

The dataset used in this project is derived from various movie datasets and contains over 47,000 entries with features such as title, genres, cast, crew, keywords, and ratings.

## Recommendations

- Input a movie you like.
- Select a preferred genre (optional).
- Set a minimum rating to filter out lower-rated movies.

## Project Structure

- `app.py`: Main application code for the Streamlit web app.
- `00-data/`: Directory containing the dataset.
- `requirements.txt`: List of dependencies required to run the application.
- `README.md`: Project overview and instructions.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request or open an issue.

## Acknowledgments

- The Movie Database (TMDB) API for providing movie posters.
- All open-source libraries and tools used in this project.
