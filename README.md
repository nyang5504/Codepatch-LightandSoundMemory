# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Nina Yang**

Time spent: **2** hours spent in total

Link to project: (https://puzzling-abiding-patch.glitch.me/)

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
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

<img src='light and sound memory.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[I did not use any outside resources to complete my work.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[One challenge that I encountered during the prework was finishing the logic in the guess function. I did not clearly what the declared global variables were supposed to be used for and thus did not know how to implement the logic to include the right variable. I overcame this by studying the flow chart given in detail. This helped me understand that guessCounter was to be used for each single guess, while progress was to keep track of what round we were up to. Each round would have progress+1 number of buttons to guess. I knew that there was a solution given by Codepath, but I really wanted to implement the logic of this function on my own, so I decided that it was my last resort. Fortunately, I was able to implement the logic myself without looking at the given solution which gave me a sense of accomplishment which makes me love coding.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[The game that I created using glitch does not include much of a back-end/database. Logins and sign-ups are often part of websites and it’s something we did not touch upon in this project. I’ve had some experience with databases, but I still have a difficult time understanding how it is incorporated and used together with the front-end.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I were to add additional features to the project, I would like to make this game continuous while also adding a score keeper. The purpose is to make the user want to beat their own scores and through it gain a sense of achievement. 8 notes might not be challenging enough for users to really enjoy.
I think that different modes of difficulty might also be a good feature to add. I would create an easy, medium, and hard mode with each working at a faster pace than the previous. Many games have such an option, and it gives the user a reason/desire to continue playing the game because it doesn’t get boring as quickly.
]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/96f82c5ebbc44de4a3db1a4ee9ca45aa)


## License

    Copyright [Nina Yang]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
