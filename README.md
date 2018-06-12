# Music-Search powered by Spotify

Angular v1.6 app for search artists and albums powered by the Spotify API.


## Summery

The data displayed in the modals are artist's albums, album's tracks and artist's tracks. I chose to emphasize again the grouping of the elements so that it's crystal clear, especially on mobile, where the boundaries of a list item are.<br>
I chose to make the list displayed scrollable and keep the pic and the details on the header always visible. This is especially useful when you are doing something along the lines of "I'm checking out a new artist's songs, so I scroll through them. Wait, how was the artist called?" and then you would have to scroll back up.<br>
I chose to immediately display the modals, even if the data is not yet available, to give the illusion of the website running faster and to display a loader in the meantime, so that the user knows the website is processing data and had not hung somewhere.<br>
Finally, I have implemented an artist's modal, in which previews of his best songs are displayed and can be played. 
I had another design choice to face here: whether or not to auto-play the previews. 
I eventually decided not to do it, since those are only 30 seconds previews and they won't represent a fully listening experience anyway, their role is just to give a hint of what the artist's style is like.

## How i created the app
- sudo yo angular
- sudo npm install -g generator-karma (if needed)

## To start the app
- `grunt serve`

## Libraries/Tools i used
- AngularJS 1.6
- Grunt
- Bower
- NPM
