# LIRI-Bot
LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

a command line node app that takes in parameters and gives you back data from Twitter, Spotify, and OMDB APIs.

before you begin please run npm install in your command line from the root folder of this project.

Enter the following commands to receive a response: node liri.js my-tweets the most recent tweets from my twitter bot

node liri.js spotify-this-song '<song name here>' This will display the song name, artist, album and a URL link to the song

node liri.js movie-this '<movie name here> This will display the movie info on the movie you typed in

node liri.js do-what-it-says this will read the random.txt file and run a command based on inputs from it

Bonus: In addition to logging the data to your terminal/bash window, LIRI-Bot outputs the data to a .txt file called log.txt too without overwriting the the file content.
