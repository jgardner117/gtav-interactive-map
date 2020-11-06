## Grand Theft Auto V Interactive Map
https://jgardner117.github.io/gtav-interactive-map/

The Grand Theft Auto V Interactive Map is a single page web application that displays *most* of the activities, stores, safehouses, and more in Grand Theft Auto V's fictional city of Los Santos. All of the points were georeferenced using the in-game map found in the pause menu, and each point displays a screenshot captured from the game relating to the Point of Interest.

The mapping library used is [Leaflet](https://leafletjs.com/). The points are stored as GeoJSON files with one file corresponding to each layer. Each GeoJSON feature has a property called *imgname* that stores the location of the screenshot that corresponds to that point.

I created this single page application specifically to be stored and used on Github to save on hosting costs. This does unfortunately mean that there is some performance issues at times with rendering the basemap. If I were to create a similar application for enterprise use I would serve the basemap as WMS tiles and the data as WFS tiles from a Geoserver instance with Postgres for data storage.


## To Do:
* Capture additional additional data to add to each point
* Add collectibles and other similar points
* Create screenshots for all points (tennis and a few others have missing images that I replaced with generic ones)
* Potentially create Geoserver instance to serve tiles and WFS to improve loading times

## Authors
* **Jesse Gardner** - *Creator* - [Github](https://github.com/jgardner117)


## Acknowledgements/Copyright information
GTA V and all associated references, images, etc. &copy; [Rockstar Games](https://www.rockstargames.com/)

Icons &copy; [Icons8](https://icons8.com/)

Screenshots from [GTA V Fandom](https://gta.fandom.com/wiki/Grand_Theft_Auto_V)
