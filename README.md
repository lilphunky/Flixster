# Flix
Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF

<img src="https://i.imgur.com/QVs4aef.gif" width=250><br>

### Notes
I ran into an error where, on launching my app, it would just show a blank black screen. I eventually figured out that I had to move the storyboard entry point to the tab controller. Previously, I had it pointed at the navigation controller that I wanted to be initially displayed.

---

## Flix Part 1 

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [x] (2pt) User can view the app on various device sizes and orientations.
- [x] (1pt) Run your app on a real device.

### App Walkthough GIF
iPhone 6s:

<img src="https://i.imgur.com/eeP5zwj.gif" width=250><br>

iPad Pro 12.9 inch (3rd generation):

<img src="https://i.imgur.com/pbkLWhb.gif" width=500><br>

### Notes
Figuring out auto layout for the first time is a bit cumbersome and messy but with some trial and error I was able to format elements how I wanted them.
