# Music Genre Classification

The main objective of this project is to classify the genre, given a Dataset of 20k rows with the following parameters:

**Rhythm** : This describes the tune of the music and its danceability. (float)\
**Vibrance** : This field refers to how energetic the music is. (float)\
**Key** : The key of a music is the group of pitches, or scale, that forms the basis of a music composition in classical, Western art, and Western pop music. (int)\
**Decibel_Levels** : This field indicates how loud the music is. For instance metal trap may be louder as compared  to trance. (float)\
**Mode** : Mode is used as a type of musical scale on the basis of a set of characteristic melodic and harmonic behaviours of the music. (numerical)\
**Lyrics_amount** : This field determines how much part of the music consists of the lyrics as compared to its pure instrumental track. Rap music may have a higher lyric_amount than Drums & Bass. (float)\
**Acoustics** : Acoustic music solely or primarily uses instruments that produce sound through acoustic means, as opposed to electric or electronic means. Eg:  string instruments, wind instruments, percussion, other instruments. This field describes how much part of the music involves acoustic instruments. (float)\
**Instruments** : This field is the opposite of Lyrics_amount and helps us understand how much part of the music involves instrumental tracks. (float)\
**Bounce** : This describes how lively the music is. (float)\
**Valence** : A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry). (float)\
**Beats_Speed** : Tempo describes the tempo at which a piece of music should be played. (float)\
**TimeLength** : The duration of the music measured in milliseconds (double)\
**Title** : Title classifies the song briefly into a subcategory. Please note that this is quite different as compared to the “Genres” attribute which is to be predicted. (Removed) \
**Hyperactivity** : This can be understood as a combination of “Beats_speed” and “valence” (float)\
**MusicEraRating** : Based on the rating of the music provided by audiences of different generations.  (int)



<b>This notebook was submitted in a Kaggle [Datathon]([url](https://www.kaggle.com/competitions/datahub-2021/leaderboard)) and secured the first place with an accuracy score of 74.867% 
