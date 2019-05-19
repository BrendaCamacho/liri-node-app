Liri is a command line app that takes user commands and returns data from the diferent API's that I used. Also, it has to be installed the next elements: dotenv, request, moment, fs. (with npm instal ...).
Also, for the spotify use, you need to visit the spotify developer page, so you can acces to you ID's

Depending on what you wrote, the next will happen:

* concert-this: it takes the name of the artist/ band and returns the name of the artist, venue, venue location andnext date of concert. With the bandsintown API

* spotify-this-song: it takes the name of the song and returns the name of the artist, the song, the album and the link to spotify. If you didn't write a song it returns you as default the information for the song: the sign  With the spotify API.

* movie-this: it takes the name of the movie you wrote and returns the title, year, cast, IMDB rating, rotten tomatoes rating, country, language and plot of the movie. If you don't write a movie it returns you as default the information for the Mr. Nobody movie, and that if you haven't seen it, you should watch it. With the OMBD API.

* do-what-it-says: it uses the readFile() to acces the text that is written on random.txt and return its information.


LINK TO VIEW THE APP WORKING: https://youtu.be/arOgI9h2hF8 
