# Music-Recommendation-System
## Introduction and Project Goals:

- Spotify creators and artists rely on user interaction to increase traffic on their profiles. In adddition to song plays, artists often make playlists of personally-recommended songs to engage with their audience. For users, Spotify may recommend its own playlists, similar artists or songs based on other user metrics or artist/song similarities. This project seeks to increase direct user interaction with artists in Spotify by building a content-based recommendation system of songs in a artist's playlist. The user will input any songs of their choosing or manually adjust Spotify audio features, and the recommender will return a list of similar songs from the playlist based on the numerical data of audio features as defined by Spotify. By suggesting playlist songs with the most similarities to a user-suggested track we aim to increase user engagement and traffic to the artist's playlist and Spotify profile.


## Data
- We will be using a 1700+ row dataset collected from the Spotify API and consisting of songs from a playlist from DJ and producer Four Tet, which can be found in the above CSV file.


## Obtaining Playlist Data
- Obtaining Playlist Data
We first access the Spotify API in order to extract playlist metadata. Spotipy is a Python library which allows developers access to the Spotify Web API upon input of their Client ID and Client Secret (these can be obtained through Spotify For Developers).


## Algorithms Used
- We select a subset of our data containing the numerical audio features. To accurately discern if a content-based recommendation system is viable for this dataset, we can cluster and visualize our data points in a two-dimensional or a three-dimensional space using K-Means clustering to determine the optimal number of clusters. We scale our data and use dimensionality reduction to visualize the data points in a two-dimensional space. For Visualization, we have done univariate, bivariate and multivariate analysis. To show the correlation among various features, a heatmap is obtained.


## Conclusion
- There are numerous approaches to solving the problem of music recommendation systems, and we became acquainted with several algorithms in depth. We gained a lot of practice skills by manipulating the dataset, changing the learning and testing sets, changing some problem parameters, and analyzing results. Though we had challenges dealing with this massive dataset, figuring out how to better explore it, and dealing with some programming details. However, with a lot of hard work, we were able to overcome all of these obstacles.

[Deployed Project](https://share.streamlit.io/jonahflateman/spotify-recommendation-system/main)
