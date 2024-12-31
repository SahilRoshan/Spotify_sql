# Spotify Dataset Analysis
This repository contains SQL queries to analyze and derive insights from a Spotify dataset. The dataset includes various attributes about tracks, artists, and albums, enabling exploratory data analysis (EDA) and addressing specific business questions.
![Spotify-Logo wine](https://github.com/user-attachments/assets/92287c76-bd5a-4417-8898-eedc3ede621c)
## Dataset Structure
The dataset consists of the following columns:
- `artist`: Name of the artist.
- `track`: Name of the track.
- `album`: Name of the album.
- `album_type`: Type of album (e.g., single, compilation).
- `danceability`: Measure of how suitable a track is for dancing.
- `energy`: Measure of intensity and activity.
- `loudness`: The loudness level of the track.
- `speechiness`: Presence of spoken words in a track.
- `acousticness`: Confidence measure of the track being acoustic.
- `instrumentalness`: Probability of the track being instrumental.
- `liveness`: Presence of a live audience.
- `valence`: Measure of musical positivity.
- `tempo`: Tempo of the track in beats per minute (BPM).
- `duration_min`: Duration of the track in minutes.
- `title`: Title of the track.
- `channel`: Channel associated with the track.
- `views`: Number of views for the track.
- `likes`: Number of likes for the track.
- `comments`: Number of comments for the track.
- `licensed`: Whether the track is licensed (TRUE/FALSE).
- `official_video`: Whether the track has an official video (TRUE/FALSE).
- `stream`: Number of streams for the track.
- `energy_liveness`: Combined metric of energy and liveness.
- `most_played_on`: Platform where the track is most played.

## Questions Answered
The SQL file includes queries to answer the following:

### Exploratory Data Analysis (EDA)
1. Display all records in the dataset.
2. Count the total number of records.
3. Count the distinct number of artists.
4. Retrieve distinct album types.
5. Identify the track with the maximum and minimum duration.
6. Identify and remove tracks with zero duration.
7. Retrieve distinct platforms where tracks are most played.

### Business Questions
1. Retrieve the names of all tracks with more than a specific number of streams.
2. Identify the artist with the highest number of tracks.
3. Calculate the average danceability and energy for all tracks.
4. List tracks with the highest combination of energy and liveness.
5. Identify the most popular track based on views and likes.

## How to Use
1. Clone this repository to your local machine.
2. Load the `spotify_query.sql` file into your preferred SQL environment.
3. Execute the queries to explore and analyze the dataset.

## Prerequisites
- A SQL-compatible database.
- Basic understanding of SQL.

## License
This project is licensed under the MIT License.

---
For any issues or contributions, feel free to open a pull request or raise an issue in this repository.

