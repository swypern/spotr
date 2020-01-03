# spotr
### Saves songs from a Spotify playlist as Deezer URLs to a file

## Setup
1. Rename `example-cred.py` to `cred.py`
2. Create a Spotify API application [here](https://developer.spotify.com/dashboard/applications)
3. Get it's Client ID and Client Secret, fill accordingly in `cred.py`
4. In your API application, click *Edit Settings* and add `http://localhost` as a *Redirect URI*
5. Fill your username from [here](https://www.spotify.com/uk/account/set-device-password/)
6. Update `playlist` to the name of your desired Spotify playlist
7. Update `filename` to the file name you want to save track URLs to

## First run
Run with `python3` and follow instructions to authenticate your account once

## Further runs
Just run with `python3`