README
Spotify playlists dataset


This dataset is based on the subset of users in the #nowplaying dataset who publish their #nowplaying tweets via Spotify. In principle, the dataset holds users, their playlists and the tracks contained in these playlists. 

The csv-file holding the dataset contains the following columns: 
"user_id", "artistname", "trackname", "playlistname"
, where
- user_id is a hash of the user's Spotify user name
- artistname is the name of the artist
- trackname is the title of the track and
- playlistname is the name of the playlist that contains this track.

The separator used is , each entry is enclosed by double quotes and the escape character used is \.



A description of the generation of the dataset and the dataset itself can be found in the following paper:

Pichl, Martin; Zangerle, Eva; Specht, Günther: "Towards a Context-Aware Music Recommendation Approach: What is Hidden in the Playlist Name?" in 15th IEEE International Conference on Data Mining Workshops (ICDM 2015), pp. 1360-1365, IEEE, Atlantic City, 2015.


