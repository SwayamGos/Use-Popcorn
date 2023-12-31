# USE POPCORN

It is a simple web application which can be used to keep track of movies and shows you have watched. I built this to practice working with the useEffect hook in react.

The project's features include:

- Search for any movie or show using the search bar and get more detailed information on it, including a plot summary(without spoilers) and IMDB ratings. This can also be used if you are interested in a particular movie or show and want to know more about it.

- Rating a movie or show of your choice. However, if you rate a movie, the application assumes you have watched it. Please DO NOT rate a movie if you havent watched it, as it also makes the user ratings less reliable.

- Adding movies to your watched list. You can add a movie to your watchlist once you have rated them. This ensures that you have watched the movie.

- Deleting movies from your watched list.

## UPDATES:

- Added local storage support. Watched movies will now be stored in the browser cache, which will enable your watched catalog to persist even after reloads. Please do not clear the cache in the browser from this website for this feature to work.

- Added keybind support!
    + Just press the enter key to activate the cursor active in the movie search bar.
    + When viewing any movie, press escape to return to your watched list.

## NOTE:

### I have used the OMDB api for fetching movies, and it only allows 1000 api requests each day in it's free tier. If you dont get the movies for some reason, most likely the application has reached the limit for fetching movies. In such a scenario, please try to revisit the application the next day.

## PROJECT LINK:

Please refer to the link in the 'About' section of the repository. If that does not work, try the link below. 
https://glittery-rugelach-e2c423.netlify.app/
