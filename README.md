# Movie Recommender System 🎬

Welcome to the Movie Recommender System app! This Streamlit web application recommends movies based on a selected movie using collaborative filtering. It utilizes movie data fetched from The Movie Database (TMDb) API to display movie posters and recommendations.

## Overview ℹ️

This app leverages Python with Streamlit 🚀 to create an interactive movie recommendation experience. It includes fetching movie data from TMDb API, computing movie similarities using collaborative filtering, and displaying recommended movies with their posters.

## Getting Started 🚀

1. **Clone the Repository**: Start by cloning this repository to your local machine.

2. **Install Dependencies**: Use pip to install required libraries.

3. **Run the App**: Launch the Streamlit app locally to start exploring movie recommendations!

## How to Use 🎥

1. **Select a Movie**: Choose a movie from the dropdown list or type its name.

2. **Get Recommendations**: The app will display top 5 recommended movies based on similarity to the selected movie.

3. **Movie Posters**: Enjoy viewing movie posters fetched from TMDb API for both the selected movie and recommended movies.

## File Structure 📂

- **app.py**: Main application script integrating Streamlit with movie recommendation functionality.
- **movie_list.pkl**: Pickled file containing movie data including titles and IDs.
- **similarity.pkl**: Pickled file containing similarity matrix for movies based on collaborative filtering.
- **README.md**: This file providing an overview and instructions for the app.



## Notes 📝

- This system uses collaborative filtering to recommend movies, which may not account for all user preferences or newer releases.
- Movie posters are fetched from TMDb API. In case a poster is not found, a placeholder image is displayed.

## Contributions 🤝

Contributions to this project are welcome! Whether you have ideas for improvements, new features, or bug fixes, we'd love to hear from you. Here's how you can contribute:

1. Fork the repository to your own GitHub account.
2. Clone the repository to your local machine.
3. Make your changes and enhancements.
4. Commit and push your changes to your fork.
5. Submit a pull request to the main repository, detailing the changes you've made and why they should be included.

I appreciate any contributions that help enhance this movie recommender system! 🙌
