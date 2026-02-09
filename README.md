# Data Engineering - Unsupervised Machine Learning, PCA and Clustering
## Project Overview
- using cluster analysis to create automated playlists out of music files
- Python code to review a data source, rescale data features, perform a principal component analysis and cluster the results
## Dataset & Sources
- Link to database files: In project folder
- Source: ~5000 songs with attributes from Spotify
- Key Features: danceability, energy, loudness, spechiness, acousticness, instrumentalness, liveness, valence, tempo
## Example Visualisations
<img width="1355" height="759" alt="silhouette_score" src="https://github.com/nicotauchmann/unsupervised_machine_learning_PCA_and_clustering/blob/e2f37601d7b8961703bb9fb19f926ebffde756d1/sample_pictures/silhouette_score.png" />
<img width="1355" height="759" alt="inertia_score" src="https://github.com/nicotauchmann/unsupervised_machine_learning_PCA_and_clustering/blob/da2461a0dbf85a4eb48f5bfbb8ffe926c9b07964/sample_pictures/inertia_score.png" />

## How to Use This Project
- import the database files and notebook into your python environment
- follow the steps outlined in the notebook
- data is skewed and unevenly distributed, so has to be rescaled
- PCA is used to improve clustering results
- code creates playlists usable for customer consumption
