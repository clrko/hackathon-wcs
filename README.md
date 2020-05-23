![Travel Memory Game](/public/img/header.png)
# Travel Memory Game
👉[The app is live here](https://travelmemorygame.netlify.app/) 👈 

The **Travel Memory Game** is a front-end web application developed on April 29th/30th during a 24h hackathon at [Wild Code School](https://www.wildcodeschool.com/en-GB) on the topic of travelling from the couch.

We decided to design a game that a user in locked down would play in order to travel by seeing webcam videos of a country of his choice. 

In order to play, you first need to select a country and a category. Then, based on these two criteria, a memory game session will be generated. The objective is to find the 8 matching cards to win an access to the webcam of the chosen country.

## The team

* Marjolaine Baratte [Github](https://github.com/marjowolff) - [LinkedIn](https://www.linkedin.com/in/marjolainebaratte/)
* Lola Donval [Github](https://github.com/Lola-D) - [LinkedIn](https://www.linkedin.com/in/lola-donval/)
* Sébastien Gruet [Github](https://github.com/SebG-prog) - [LinkedIn](https://www.linkedin.com/in/sebastien-gruet/)
* Lena Hailin Sim [Github](https://github.com/Lenasim) - [LinkedIn](https://www.linkedin.com/in/lena-hailin-sim/)
* Claire Kodia [Github](https://github.com/clrko') - [LinkedIn](https://www.linkedin.com/in/clairekodia/)
* Aristide Ouedraogo[Github](https://github.com/ariomega) - [LinkedIn](https://www.linkedin.com/in/aristide-ouedraogo/)

## The project

The projet has been developed as part of the web developement training program at [Wild Code School](https://www.wildcodeschool.com/en-GB) during a 24h hackathon (April 2020). 

Developing a game has been a good way to materialize what we had been learning during the first one and half months of the program, to consolidate our skills in React.js, to manipulate data using an API and learn how to use the React.js State Hooks.
 
## Features


* Choice between multiple countries
* Choice between 6 images categories
* Game session to try and find the 8 matching pairs
* Access to the webcams of the choosen country at the end of the game session

## Technologies

* React.js (State Hooks)
* JavaScript
* HTML5
* CSS3

## Hosting

* Netlify 

## API used

* [Pixabay](https://pixabay.com/api/docs/): we got from the api the images to be displayed in the game session based on 2 parameters: the country and the category (beach, nature etc.)
* [Windy](https://api.windy.com/webcams/docs): we got an access to a repository of webcams based on the country selected by the user.

## Screenshots

<div style="display:flex; justify-content:space-around; margin:30px 0;">
<img src="/public/img/travel_memory_game_homepage.png" alt="homepage desktop" style="width:200px heigth:auto"/>
<img src="/public/img/travel_memory_game_gamesession.png" alt="game session desktop" style="width:200px heigth:auto"/>
<img src="/public/img/travel_memory_game_webcam.png" alt="webcam desktop" style="width:200px heigth:auto"/>
</div>


## In the project directory, you can run:
* `npm install`
* `npm start`

These commands install the dependencies and start the app in the developement mode.