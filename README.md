# The Wrexham F.C Quiz

The purpose of this website is to test peoples knowledge of Wrexham Football Club in the 2023/2024 season. The site is aimed at people who are already familiar and fans of the club and want to test how much they know about it. The website allows the users to submit their scores to a high score page so they can play with they're friends. 

/*insert images of mock up here*/

## Features 
* Home page
    * The home page includes 3 different buttons for the user to choose from, play, how to play and highscores.
    * The home page is accessible from every other page using the home button. 
    
![Home page](documentation/home-page.jpg)

* Header 
    * The header is simple with the quiz title and the football clubs badge. 
    
![Header](documentation/header.jpg)

* Difficulty page
    * This page is accessed when the user clicks play on the home page.
    * This page gives the user to options either easy or hard, and also a home button to return to the home page. This button is accessible on all pages apart from the home page. 
    
![Difficulty choice](documentation/difficulty-page.jpg)

* Easy quiz question page
    * The user is shown a question and will be given two answers to choose from, they have a one minute time limit to answer this question.
    * A next question button will be underneath the answers and can be clicked to move onto the next question. 
   
![Easy quiz questions](documentation/easy-quiz.jpg)

* Hard quiz question page
    * Similar to the easy questiion page but the questions are harder and there is now a choice of four questions instead of two. 
    
![Hard quiz questions](documentation/hard-quiz.jpg)

* Submit high scores form
    * This form appear after the user has been through all the questions, the user can submit their name and submit their score to the highscore page. 
    
![Submit high scores form](documentation/submit-form.jpg)

* High score page
    * On this page the users can see all their highscores they have submitted and they can also clear the highscores page user the the clear highscores button.
    
![high scores page](documentation/high-score.jpg)

* How to play
    * This is where the user can come if they are unsure on how to play the game and it gives them a step by step guide. 

![How to play](documentation/how-to-play.jpg)

### Game Buttons on home page
* The play button
    * This is the button the user will press if they want to go straight into the game.
* How to play
    * This button is for users who would like to know how to play the game.
* Highscore button
    * Takes the user to the highscores page to see their previous scores. 


### Easy Mode

The easy mode only has a 50/50 choice so there is less chance of getting the answer wrong, also the questions are slightly easier. Difficulty is selected before entering the quiz page. 

### Hard Mode

This mode is harder as it has 4 different answers to choose from, but also the questions will be slightly harder. If the player selects the correct answer it will light up green, if they select the wrong answer it will light up red and the correct answer will light up green, the purpose of this is allow the user to learn whilst playing the game. 

## User Experience

### First time visitors
* As a first time visitor I want to learn how to play the game, they will do this by entering the how to play page.
* I should easily be able to begin the game and select a difficulty of choice. 
* I will be able to gain knowledge and not just play the game so when I return I will improve if I try to play again. 

### Second time visitors
* On the second visit I will be able to go straight into the game without needing to look how to play.
* I will feel more confident and will want to try the harder level as I found the easy level to easy.
* I want to be able to compare my scores with my friends, so we can compete against eachother.  


### Design Choices
* Colour Scheme
    * The two main colours used were red (#ef4136) and green (#226e57). These colours were chosen as they are the main colours associated with Wrexham AFC. White was used for the text as it makes it more appealing. 
* Typography
    * The font used was Roboto, with sans-serif set as a back up font. Roboto was used as it has an easy readibility and has a clean and modern design. 
* Imagery
    * The background image used was taken at the Wrexham AFC home ground and makes for a well suited background image. Also the Wrexham AFC badge was also added to follow the Wrexham theme. 


### Wireframes
* All wireframes were created using Balsamiq wireframes, all designs for desktop, tablet and mobile are linked [here] /*add balsamic link here */

### Testing
* The W3C CSS validator and the W3C Markup Validator were used to validate every page of the project to make sure there were no syntax errors.

    * [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) [Result](documentation/css-validation.jpg)
    * [W3C Markup Validator](https://validator.w3.org/) - Results for each page are below
        * [Home page](documentation/index.html-valdidation.jpg)
        * [Difficulty page](documentation/difficulty-level.html-validation.jpg)
        * [Easy questions](documentation/easy-level.html-validation.jpg)
        * [Hard questions](documentation/hard-level.html-validation.jpg)
        * [High score page](documentation/highscore.html-validation.jpg)
        * [How to play page](documentation/how-to-play.html-validation.jpg)
    * [JSHint](https://jshint.com) - Results for each JavaScript file are below
        * [Quiz page](documentation/play.js-jshint-validation.jpg)
        * [Difficulty page](documentation/difficulty.js-jshint-validation.jpg)
        * [High score page](documentation/highscore.js-jshint-validation.jpg)

#### Testing User Stories

* First time visitor goals
    * As a first time visitor I want to learn how to play the game.
        * The user can easily do this by clicking on the how to play button on the home screen, this then takes them to the how to play page where they are shown clearly a step by step guide on how to play the game.
    * I should easily be able to play the game and choose a difficulty
        * When the user is ready to play the game they click the play button this takes them to the page where they can choose between easy or hard difficulty, when they click on either one they then move onto the quiz with the corresponding difficulty level questions. 
    * I want to be able to gain knowledge
        * The user gains knowledge on each question as they will be told the correct answer even if they choose the wrong one. Allowing them to learn as they play. 

* Second time visitor goals
    * I will be able to go straight into the game
        * As the player already knows how to play from their previous visit they can just go straight into the game. 
    * I will feel more confident and choose a harder difficulty level
        * As the user has gained knowledge from their previous visit as they foudn out the correct answers even if they answered them wrong. They will have more confidence to try the harder level.
    * I want to be able to compare my scores with my friends
        * Users can do this by either playing on the same device and going to the highscores page and looking at all of their scores. Or they can show eachother their scores on their own devices and compare, if they want to reset the scoreboard they can press the clear high score button. 

* Future visitor goals
    * The future plan is to add more than ten questions in each difficulty level and then pick ten different questions from random to add variety to the quiz. 

### Further testing
*   

## Credits
### Image Credits
* The Wrexham Badge was taken from https://www.cleanpng.com/png-racecourse-ground-wrexham-a-f-c-national-league-ch-5009892/#google_vignette 
* The background image was taken by myself.