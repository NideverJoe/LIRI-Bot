# LIRI-Bot   ---  CLI APP

## Purpose
#### User can make requests using the command to line to make a variety of API calls. Reply comes back in the terminal.

## Technologies Used
* javascript
* node.js
* axios.js
* moment.js
* fs.js

* APIs
  * BandsInTown
  * Spotify
  * Open Movie Database
  
## Overview
#### User make a request with the following syntax:
#### node liri **Query Type** **"Query Data"**

* Query Types
  * concert-this       Calls BandsInTown API and shows the soonest performance for performer requested
  * spotify-this-song  Calls Spotify API and displays artist and album information
  * movie-this         Calls OMDB API and displays movie info including cast, bio, and more.
  * do-what-it-says    Special Case - Pulls commands from random.txt file using the fs package and runs it.
  
* Query Data
  * takes in user input and passes it into the appropriate function for each API
  * placeholder data is used for each **Query Type** in the event that the user does not provide this parameter

## See gif below of the app in action.
![Liri Node App](https://user-images.githubusercontent.com/50809345/60522243-3e00e780-9cae-11e9-847e-c8ebe5cff5fb.gif)
