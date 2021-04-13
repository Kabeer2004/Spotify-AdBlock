# Spotify-ad-blocker v1

made by @Kabeer2004 and @Aarya-Gosar

https://github.com/Aarya-Gosar
https://github.com/Kabeer2004

thanks @Aarya-Gosar for making my idea come to life 😁

Usage:

Open the python script in a text editor of your choice and set path and SPOTIFY_ACCESS_TOKEN values as follows.

for path, put the path where Spotify.exe is located on your computer. use double backslashes (\\) because that is how python works
example -
path = 'C:\\Users\\User1\\AppData\\Roaming\\Spotify\\Spotify.exe'

for SPOTIFY_ACCESS_TOKEN, go to https://developer.spotify.com/console/get-users-currently-playing-track/?market=&additional_types= 
there, login and click the green Generate Token button. select ONLY the user-read-currently-playing checkbox and click Request Token.
copy the request token and paste it as it is within the single quotes ''
example-
SPOTIFY_ACCESS_TOKEN = 'BQBeofHqu1HgfZOnEWef8Fh4rMfdfvgr0bbgjwwYV_4r8qJiH2UUlrGBsPon9fVEDjopIgWmHnPrLA1Dl5RCb62p2jz0p_fiw6GL5psmChFz1mQA_bK3rQmHOEbIduz1IXpZJ7sO7ETY7_TXRSx_aaBR6dUbXETFmKeE'

Save the file and run it with python!


Known bugs-

You could get an error message for the following reasons:
-1. the script cannot access the Spotify.exe path because of permissions set on it. this is usually the case if Spotify was installed from 
the windows store. uninstall this version and download spotify from https://www.spotify.com/us/download/windows/ and click the Download button
-2. the access token is invalid. if this is the case, just regenerate an access token using the steps given above

Working on a v2 where all this becomes way easier.