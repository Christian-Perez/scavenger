## <SCREENSHOT>

##Description
  <scavenger> is a single player scavenger hunt game played on a mobile app. Players can start scavenger hunts from a hunt template provided by an api. Each hunt will have a description, duration, objectives, & a map defining the boundaries of the playing field. A hunt objective has a title, description/riddle, and an input field for checking a user's answer against the answer key. The objective of <scavenger> is to solve all the riddles or "objectives" in a hunt <before time runs out> OR <as fast as possible>.

### Plans for Further Development
- Multiplayer Events - Players will be able to join 'Hunt Events' with specific start / end times
- Team Games - Players can create / join teams & play against other single players or teams

##Technologies used:
- HTML
- CSS
- JAVASCRIPT
- Ionic
- Angular-google-maps
- Ruby on Rails
- jwt Gem * 
- devise
- PostgreSQL

##Approach Taken
  I plan to begin building <scavenger> by building out an api to serve hunts, excluding map data, to the client app (ionic app).

  Once i can request all the information needed from the api & associate that information with a user(user id, not jwt) through authentication i will begin building the ionic app to consume the api

  Once the api and app can both handle hunts I'll begin implementing the map's feature



###stretch goals

  fully implement CRUD for Hunts in both the api and Ionic App

  Add a Team Play feature where users can create / join teams and compete agains each other to complete hunts faster than their opponents

##Installation Instructions

##Unsolved Problems

##ERD
![ERD](https://github.com/chrisdillon92/scavenger/blob/master/resources/ERD.png "ERD")

##Wireframes
![wireframe 1](https://github.com/chrisdillon92/scavenger/blob/master/resources/wire%201.png "wireframe 1")

![wireframe 2](https://github.com/chrisdillon92/scavenger/blob/master/resources/wire%202.png "wireframe 2")

![wireframe 3](https://github.com/chrisdillon92/scavenger/blob/master/resources/wire%203.png "wireframe 3")

![wireframe 4](https://github.com/chrisdillon92/scavenger/blob/master/resources/wire%204%20stretch.png "wireframe 4")

##Routes

##auth Requirements

##Trello
https://trello.com/b/VfFSaWHh/scavenger

##Heroku / App Download Instructions or link
