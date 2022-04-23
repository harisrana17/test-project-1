# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Haris Rana

Time spent: **10** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com/edit/#!/dust-petal-armchair?path=script.js%3A103%3A3)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/Z7bNsKL.gif)
)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[I had used some resources that such as my previous notes from a class I took on HTML, CSS, and JavaScript, as well as the w3schools and khanacademy website. I utilized there resources only for problems regarding syntax.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)  
[When working on the project I had encountered a challenge when trying to adjust the playing speed each turn. The problem I had encountered was that the playback speed would change for each turn but would not reset whenever the user finished the game or pressed the stop button. I decided to track back and test all the code that I had changed while implementing this function and had found the issue after debugging for 20 minutes. The issue was related to the need to reset the clueholdtime variable back to its original number of 1000 every time the stop or start function is called and when the game is over.Once I reset the variable clueholdtime in each of these functions the problem was resolved and worked how I wanted it to.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[While working on this project I enjoyed learning the process and methods that front-end and back-end developers utilize when working on a project. This project was a simple and straightforward process that provided me with instructions to be able to finish this project alone as a fullstack developer. However real world projects would usually require multiple developers and teams on the front and back end to finish the project. With this in mind I was wondering how front end and back end developers collaborate efficiently on a project. More specifically, I wanted to know if the backend of a website was created as the backbone for front end development or vice versa. Could frontend and backend development be done simultaneously or does one need to be incorporated first.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[If I had more time to work on this project, I would utilize the time to add another feature. The specific feature I would add would be a survival mode feature. This mode would be activated by clicking the button labeled survival mode on the screen. The game would then prompt the user to enter a name which would be used to keep a tally of the highest scores. When clicked the sequence of patterns would go on for an unlimited amount of time until the user gets the sequence wrong. The mode would also include a score counter on screen for the number of correct sequences guessed by the user. Once the user loses the game the highest scores list would be displayed with the user’s inputted name and their high score. It would also display the user’s most recent name and score whether or not it was a high score.
]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/UYn9fH7urak)


## License

    Copyright [Haris Rana]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
