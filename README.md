## <SCREENSHOT>

##Description
  <scavenger> is a single player scavenger hunt game played on a mobile app. Players can start scavenger hunts from a hunt template provided by an api. Each hunt will have a description, duration, objectives, & a map defining the boundaries of the playing field. A hunt objective has a title, description/riddle, and an input field for checking a user's answer against the answer key. The objective of <scavenger> is to solve all the riddles or "objectives" in a hunt <before time runs out> OR <as fast as possible>.
####Link To Rails 5 API Repo
https://github.com/chrisdillon92/scavenger_api
####Link To Ionic Project Repo
https://github.com/chrisdillon92/scavenger_ionic
####To test Ionic App On Your Device
 - Download Ionic View from Google Play or the App Store
 - use app id 4a06f62a
 OR
 - fork / clone this repository to your local machine
 - navigate to your app
 - connect your phone & allow file transfers
 - run 'ionic run' to install app on your local phone (aditional steps may be required for iphones)

### Plans for Further Development
- finish implementing MVP :P
- Multiplayer Events - Players will be able to join 'Hunt Events' with specific start / end times
- Team Games - Players can create / join teams & play against other single players or teams

##Technologies used:
- HTML
- CSS
- JAVASCRIPT
- Ionic
- Angular-google-maps *
- Ruby on Rails
- jwt Gem *
- devise *
- PostgreSQL

##Approach Taken
  I plan to begin building <scavenger> by building out an api to serve hunts, excluding map data, to the client app (ionic app).

  Once i can request all the information needed from the api & associate that information with a user(user id, not jwt) through authentication i will begin building the ionic app to consume the api

  the last step will be implementing the map's feature

  ___

  I began by building enough of the api to populate a hunt in my ionic app

  after i could request the needed json from the api i began building out views in the front end.

  after resolving blockers, i was able to create functionality to update the player_objectives from the front end, but what i think is an ionic scoping issue with the function is preventing me from moving forward.
  - i know that the database is being updated, but i'm unable to apply the style or update the html of the DOM Element to visually notify the user that the DB is updated.

###stretch goals

  fully implement CRUD for Hunts in both the api and Ionic App

  Add a Team Play feature where users can create / join teams and compete agains each other to complete hunts faster than their opponents

##Installation Instructions

##Unsolved Problems
  markCompleted function does not work when populating the page, but works when answering a question. So, even if an objective is completed, it will show up as incomplete when the app is reloaded.

##ERD
![ERD](https://github.com/chrisdillon92/scavenger/blob/master/resources/ERD.png "ERD")

##Wireframes
![wireframe 1](https://github.com/chrisdillon92/scavenger/blob/master/resources/wire%201.png "wireframe 1")

![wireframe 2](https://github.com/chrisdillon92/scavenger/blob/master/resources/wire%202.png "wireframe 2")

![wireframe 3](https://github.com/chrisdillon92/scavenger/blob/master/resources/wire%203.png "wireframe 3")

![wireframe 4](https://github.com/chrisdillon92/scavenger/blob/master/resources/wire%204%20stretch.png "wireframe 4")

##Routes
/hunts/:hunt_Id >> returns json of hunt & all data required for displaying/updating hunt.

##auth Requirements

none yet

##Trello
https://trello.com/b/VfFSaWHh/scavenger

##Heroku / App Download Instructions or link
