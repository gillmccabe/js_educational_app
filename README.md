# JS Educational App

A week-long group project created using JS, Google Maps API, our own custom API and MongoDB.
Our initial brief was to create an interactive educational web app that displays information in a fun and interesting way.  

From this brief we designed, planned and developed a web app which displays the spread of infectious diseases across the world over several centuries and provides the user with facts about each disease. 


## Our MVP

- Should be able to select a disease from a list of diseases
- Upon selecting a disease, markers should be placed on the map to show where the disease is prevalent
- Should be able to add more than one disease to the map at once
- On clicking on a map marker, an info-window should pop up to provide information about that disease 


## Screenshots

Planning Process:

<img width="700" alt="screen shot 2016-10-06 at 14 56 28" src="https://cloud.githubusercontent.com/assets/17990363/19608417/190b5844-97c9-11e6-86af-9809676254c7.png">


Main Page, displaying results of selected diseases on map:

<img width="700" alt="screen shot 2016-10-22 at 23 51 06" src="https://cloud.githubusercontent.com/assets/17990363/19623052/cee15f9e-98b2-11e6-8da8-14c6983a8372.png">


Extra information provided by clicking on markers:


<img width="700" alt="screen shot 2016-10-22 at 23 52 29" src="https://cloud.githubusercontent.com/assets/17990363/19623056/dc4f7a9e-98b2-11e6-9e32-ec1c1203791e.png">


Graphs Displaying Overall Data:

<img width="700" alt="screen shot 2016-10-22 at 23 52 51" src="https://cloud.githubusercontent.com/assets/17990363/19623058/e54d5db4-98b2-11e6-9ecb-e2ca440f0cbe.png">



### To run app >>
npm install to pull down node modules

run nodemon server.js

run webpack -w from client folder

run mongod and mongo < db_seeds.js from the seeds folder
