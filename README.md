# Python-Web-Scraping
Simple command line scrapers to download music,get song details and get lyrics. Supply song and artist names in command line arguments.

USAGE :-

Mp3Skull Scrape
./download.py [FLAGS] SEARCH_QUERY
-r, --remix	If the song is a remix.
-c, --cover	If the song is a cover.
-s, --short	If the song length is under 90 seconds.
download.py also uses song_details.py to put the required metadata.

./song_details.py [FLAGS] SEARCH_QUERY

Automatic Lyrics Finder
./lyricsfinder SEARCH_QUERY

Integration with Rhythmbox coming up...
