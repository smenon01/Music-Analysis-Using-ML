# Music Analysis using Machine Learning

## Problem Description

What is it that attracts a person to a song? Music is an essential part of our lives, and one of the most accessible and respected forms of art in our society, but truly understanding what aspects contribute to our enjoyment is a continuing process. As the global music industry continues to grow in revenue—in part from the rise of streaming services—and provide us with new ways to explore emerging artists, learning more about how we interact with music is becoming more important than ever to remain relevant and successful in the field<sup>1</sup>.

With this in mind, for our project, we were attempting to improve a user’s experience in music selection through classification of song *genre, mood,* and *popularity.* When a user listens to a track or builds a playlist, they may want to categorize their songs with respect to an intersection of these three mentioned aspects, and our models could help in producing an outcome playlist or sorted tracks. Creating a better understanding of what factors contribute to people’s enjoyment of music could help in designing more effective recommendation systems. All three tasks mentioned above can be considered classification problems.

## Dataset
We utilized the [Spotify Tracks DB dataset](https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-db), which contains audio features and metadata for tracks taken from the Spotify API. This dataset contains 232,725 records (songs) with 18 variables. Since we have three tasks, the response variables include popularity, genre, and valence, and may require some transformation to run classification models. 
Feature types include audio information (such as energy, danceability, loudness) and song/artist metadata (including artist_name, genre, track_name) for an individual track. There are both continuous features (duration_ms, tempo) and categorical features (key, track_id) in the dataset.

## References
1. Nusca, A. (2019, October 21). Spotify saved the music industry. Now what? Fortune. https://fortune.com/longform/spotify-music-industry-profits-apple-amazon/
