# Intro
The script will get your currently playing song on Spotify and automatically grab the lyrics

# Setup
Export your Spotify Username and PW as environment variables and then start the script.  e.g.  

```
export SPOTIFY_USER=usernamehere
export SPOTIFY_PW=pwhere
python3 __main__.py
```


# Credits
Forked from https://github.com/PappaStalin/Spotify-Lyrics  

I have refactored to use the simpler oauth mechanism, and removing dependency on Spotipy which caused a tricky setup process.
