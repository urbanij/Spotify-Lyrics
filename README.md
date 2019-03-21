# Intro
The script will get your currently playing song on Spotify and automatically grab the lyrics.

# Setup
## Install requirements
`pip3 install -r requirements.txt`

## Start program
Export your Spotify Username and PW as environment variables and then start the script.  e.g.  

```
export SPOTIFY_USER=usernamehere
export SPOTIFY_PW=pwhere
python3 spotifylyrics.py
```


# Credits
Originally forked from https://github.com/PappaStalin/Spotify-Lyrics  

I have refactored code to my tastes, including switching to use the simpler oauth mechanism / removing dependency on Spotipy and HTTP servers, which caused a tricky setup process.
