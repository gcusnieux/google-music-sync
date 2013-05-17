GoogleMusicSync
===============

A simple Python script to sync your local MP3 library to Google Play Music.
Uses the excellent Google Music API script by Simon Weber and eyeD3 for MP3 tag reading.

To run it, you'll need the pre-reqs:

Google Music API
  pip install git+git://github.com/simon-weber/Unofficial-Google-Music-API.git@develop
  
eyeD3
  pip install eyeD3
  
The script accepts two parameters:
./googlemusicsync -p LOCAL_PATH -s 'true/false'

Where
-p is the local path that you wish to scan
-s should the changes be synced, or just report the differences.

Please note at the moment that this script is simply one way, any files that 
are on your local machine that are not on Google Play Music will be synced.