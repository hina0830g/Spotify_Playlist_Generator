<h1 align="center"> 🎵 Custom Spotify playlist generator 🎵 </h1>
For those who enjoy a wide range of genres, the existing song recommendation algorithm often struggles to find cohesive patterns in music preferences due to the inherent complexity of diverse music preferences. <be>
<p></p>

I developed a personalized playlist generator algorithm in Python to address this challenge, focusing on refining music preferences by genre. The key highlight is the algorithm's ability to incorporate existing playlists (ideally categorized by genres), artist lists, and specific genres to fine-tune music recommendations. This approach results in tailored playlists for each preferred genre, ensuring an individualized experience that remains uninfluenced by other music categories. It is possible to incorporate additional parameters, such as tempo preferences, to further refine the selection. Remember, the more coherent the tracks in the playlists and artists you give, the better recommendations you will get. 🙂
<h2 align="center"> Code </h2>

- [**Playlist_Generator.ipynb**](https://github.com/hina0830g/Spotify_Playlist_Generator/blob/main/Playlist_Generator.ipynb) 
This is the playlist generator. Make sure you have a Spotify For Developers account and have your credentials. <br>

<h2 align="center"> Parameters </h2>
(examples of target parameters) <br>
- Genres: Pop, r-n-b, rock, indie, etc <br>
- Seed Artists: give a list of artist names to be used in the algorithm; something like ["artist name 1", "artist name2"] <br>
- Seed Playlists: give a list of playlists to be used in the algorithm; ["URL1", "URL2"] <br>
