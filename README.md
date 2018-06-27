## Popular Movies Stage 1

#### Project Overview
Most of us can relate to kicking back on the couch and enjoying a movie with friends and family. In this project, you’ll build an app to allow users to discover the most popular movies playing. We will split the development of this app in two stages. First, let's talk about stage 1.

In this stage you’ll build the core experience of your movies app.

Your app will:

* Present the user with a grid arrangement of movie posters upon launch.
* Allow your user to change sort order via a setting:
  * The sort order can be by most popular or by highest-rated
  
* Allow the user to tap on a movie poster and transition to a details screen with additional information such as:
original title
  * movie poster image thumbnail
  * A plot synopsis (called overview in the api)
  * user rating (called vote_average in the api)
  * release date


## Rubric

Meets Specifications
Congrats! Your hard work has paid off! Keep up the good work as you continue your Nanodegree journey! Safe journey and bon voyage! :smile:

Stay :udacious:!

### Common Project Requirements
- [x] App is written solely in the Java Programming Language.

- [x] Movies are displayed in the main layout via a grid of their corresponding movie poster thumbnails.

- [x] UI contains an element (i.e a spinner or settings menu) to toggle the sort order of the movies by: most popular, highest rated.

- [x] UI contains a screen for displaying the details for a selected movie.

- [x] Movie details layout contains title, release date, movie poster, vote average, and plot synopsis.

- [x] App utilizes stable release versions of all libraries, Gradle, and Android Studio.

### User Interface - Function
- [x] When a user changes the sort criteria (“most popular and highest rated”) the main view gets updated correctly.

- [x] When a movie poster thumbnail is selected, the movie details screen is launched.

### Network API Implementation
- [x] In a background thread, app queries the /movie/popular or /movie/top_rated API for the sort criteria specified in the settings menu.

### General Project Guidelines
- [x] App conforms to common standards found in the Android Nanodegree General Project Guidelines (NOTE: For Stage 1 of the Popular Movies App, it is okay if the app does not restore the data using onSaveInstanceState/onRestoreInstanceState)

![1](https://user-images.githubusercontent.com/5784029/40395370-b8acd0a0-5df5-11e8-8ca4-e8a2a05ea756.png)

A Setting Menu allows the user to select between Popular Movies and Top Rated movies to display in the
GridView. (Favorites option has not been implemented yet.)

![2](https://user-images.githubusercontent.com/5784029/40395598-e020058e-5df6-11e8-812f-69bd6697128d.png)

Clicking a movie image in the GridView takes the user to the Movie Detail Activty and displays data about
the selected movie. The Status Bar and Action Bar display the average color of the movie backdrop image
using an algorithm that averages the pixel colors. Palette with Picasso sometimes generates an empty
swatch so I chose to use the average color algorithm.

![screenshot_2018-05-27-23-12-18_resized](https://user-images.githubusercontent.com/5784029/40595664-fe9acdc6-6203-11e8-8380-8dbe0edbfa73.png)
