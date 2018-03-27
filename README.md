# LIRI
The eigth assingment for UNC Coding Bootcamp.
In this assignment, I made LIRI. LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI is a command line node app that takes in parameters and gives you back data.

### Instructions

liri.js can take in one of the following commands:

* `my-tweets`

    * This will show your last 20 tweets and when they were created at in your terminal/bash window.

* `spotify-this-song`

    * This will show the following information about the song in your terminal/bash window

        * Artist(s)

        * The song's name

        * A preview link of the song from Spotify

        * The album that the song is from
    
    * If no song is provided then your program will default to "The Sign" by Ace of Base.

* `movie-this`

    * This will output the following information to your terminal/bash window:

     ```
       * Title of the movie.
       * Year the movie came out.
       * IMDB Rating of the movie.
       * Rotten Tomatoes Rating of the movie.
       * Country where the movie was produced.
       * Language of the movie.
       * Plot of the movie.
       * Actors in the movie.
     ```

   * If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'

* `do-what-it-says`

    * LIRI will take the text inside of txt file and then use it to call one of LIRI's commands.

- - -

## Built With

* javascript

* node packages

    * twitter
    * node-spotify-api
    * request
    * dotenv

* Twitter API

* Spotify API

* OMDB API