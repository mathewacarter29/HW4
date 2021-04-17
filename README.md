# HW4
# Flix
Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

---

## Flix

### User Stories

#### REQUIRED (10pts)
- [x] (70pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.
- [x] (10pts) Views should be responsive for both landscape/portrait mode.
   - [x] (5pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [x] (5pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.
- [x] (20pts) Improved the user interface by experimenting with styling and coloring.

### App Walkthough GIF

<img src="https://github.com/mathewacarter29/HW4/blob/master/HW4Walkthrough.gif" width=250><br>

### Notes
I followed the tutorial for this app given at the following URL: https://www.youtube.com/playlist?list=PLrT2tZ9JRrf6_xXjDCX6mwhhGjJf0_Cdl
The walkthrough was very straight forward and easy to follow along with.
The biggest challenge with this app was making the UI pleasant. I first made the background black by changing the background color of the RecyclerView in the MainActivity xml file.
Within the item_movie.xml class, I made the movie title and movie overview follow a style I created which made the text white as well as centering the text and bringing it to the
top of the TextView.

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids

