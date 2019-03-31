# Intro
The script will get your currently playing song on Spotify and automatically receive the lyrics over Telegram, via a bot.


[![img](https://i.imgur.com/azAl0PJ.png)](https://youtu.be/pVYoDo22Nq8)


# Setup
## Install requirements
`pip3 install -r requirements.txt`

## Start program
Export your Spotify Username and PW as environment variables and then start the script.  e.g.  

```
export SPOTIFY_USERNAME=usernamehere
export SPOTIFY_PASSWORD=pwhere
export SPOTIFY_LYRICS_BOT_TOKEN=tokenhere
export MY_TELEGRAM_ID=idhere

python3 spotifylyrics.py
```


# Credits
Forked from https://github.com/richstokes/Spotify-Lyrics
original repo: https://github.com/PappaStalin/Spotify-Lyrics

I have added basic Telegram support.