# cmse201-finalproject

### Project Title: Analyzing What Makes a Song "Danceable" and Its Relation To Its Frequency in Spotify Playlists

### Research Question: What makes a song danceable, and does the danceability of a song affect its popularity? (According to Spotify)

###### Description: 
I explored the "Most Streamed Spotify Songs 2023" dataset on Kaggle, which includes various musical attributes, from basic details like song duration and key to deeper insights such as valence, speechiness, and energy. Valence measures a track's positivity, speechiness detects spoken words, and energy reflects a song's intensity. One feature that stood out was danceability, which Spotify defines as a track's suitability for dancing, based on tempo, rhythm stability, beat strength, and regularity. This sparked questions about how danceability relates to other attributes like bpm, valence, speechiness, and energy, and whether it impacts a track's popularity.

In summary, this analysis of the "Most Streamed Spotify Songs 2023" dataset reveals insights about danceability's relationship with other musical characteristics:

BPM: Highly danceable songs typically range between 100-140 bpm, peaking around 120 bpm, as this range provides a comfortable tempo for dancing.
Speechiness: Danceable songs tend to have low speechiness, aligning with the idea that music is more danceable when it contains less spoken content.
Energy: Danceability seems to increase with energy, indicating that high-energy tracks are generally more danceable.
Valence: There is a moderate positive correlation between valence and danceability, suggesting that more positive, cheerful songs are easier to dance to.
Popularity: Danceability does not strongly correlate with popularity. Popular songs span various styles, tempos, and tones, reflecting diverse listener tastes.

The project faced challenges, including organizing the data by popularity and handling unexpected data entries. The decision was made to use playlist frequency as a proxy for popularity, and the analysis suggests that while danceability contributes to a song's appeal, it doesn’t necessarily drive popularity. Future work could include handling data issues to explore additional popularity metrics and relationships with other musical attributes.