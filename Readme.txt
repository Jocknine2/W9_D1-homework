1.What is responsible for defining the routes of the games resource?
gamesRouter

2.What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?
client is responsible for the front end (visuals) and the server is responsible for back end (data management).

3.What are the the responsibilities of server.js?
to connect to the localhost database.
cors is a patch that enables js to accept db's from 2 localhosts
createRouter sets the connector between the front end and backend via gamesRouter
and the listen sets the localhost of the given db.


4.What are the responsibilities of the gamesRouter?
gamesRouter is responsible for all CRUD actions with the db.

5.What process does the the client (front-end) use to communicate with the server?
fetch methods to acquire information from the db.

6.What optional second argument does the fetch method take? 
And what is it used for in this application? Hint: See Using Fetch on the MDN docs
init which allows the fetch to control a number of different settings.

7.Which of the games API routes does the front-end application consume (i.e. make requests to)?
GET
POST
DESTROY 


8.What are we using the MongoDB Driver for?
to allow the app to access the mongo db in Javascript.
