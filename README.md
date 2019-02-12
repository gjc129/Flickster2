Name: Gabriel Cabrera

Date Last Modified: 2/11/2019

Total Hours: 21 hours

## Flix Part 2

### User Stories

- [x] Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x] Allow video posts to be played in full-screen using the YouTubePlayerView.

#### BONUS

- [ ] Trailers for popular movies are played automatically when the movie is selected 
  - [ ] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
  - [ ] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [ ] Add a play icon overlay to popular movies to indicate that the movie can be played.
- [ ] Apply the popular ButterKnife annotation library to reduce view boilerplate. 
- [ ] Add a rounded corners for the images using the Glide transformations.

### App Walkthough GIF


<img src="https://github.com/gjc129/Flickster2/blob/master/flickster2part2walkthrough.gif" width=250><br>

### Notes

The issues that I encountered throughout this project were mostly syntax errors in which I added an extra character or were missing a character.

## Open-source libraries used
- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## Flix Part 1


- [x]  User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.

#### BONUS
- [x] Views should be responsive for both landscape/portrait mode.
   - [x] In portrait mode, the poster image, title, and movie overview is shown.
   - [x] In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.

- [ ] Display a nice default [placeholder graphic](https://guides.codepath.com/android/Displaying-Images-with-the-Glide-Library#advanced-usage) for each image during loading
- [ ] Improved the user interface by experimenting with styling and coloring.
- [ ] For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

### App Walkthough GIF

<img src="https://github.com/gjc129/Flickster2/blob/master/flickster2walkthrough.gif" width=250><br>

### Notes
I had issues at first because I was using constraint layout instead of relative layout for the xml design files. I also had some issues with debugging but those were resolved after some thorough scanning of the code for typos and small syntax errors. Also had to restart from scratch at one point because app was not responding and couldnt figure out why

### Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
