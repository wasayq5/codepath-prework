# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Abdulwasay Qureshi

Time spent: 4 hours spent in total

Link to project: https://glitch.com/edit/#!/amazing-congruous-preface

## Required Functionality

The following **required** functionality is complete:

- [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [X] "Start" button toggles between "Start" and "Stop" when clicked.
- [X] Game buttons each light up and play a sound when clicked.
- [X] Computer plays back sequence of clues including sound and visual cue for each button
- [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [X] User wins the game after guessing a complete pattern
- [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [X] Buttons use a pitch (frequency) other than the ones in the tutorial
- [X] More than 4 functional game buttons
- [X] Playback speeds up on each turn
- [X] Computer picks a different pattern each time the game is played
- [X] Player only loses after 3 mistakes (instead of on the first mistake)
- [X] Game button appearance change goes beyond color (e.g. add an image)
- [X] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [X] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![Losing Game](https://s7.gifyu.com/images/Screen-Recording-2022-04-01-at-7-1.gif)
![Winning Game](https://s7.gifyu.com/images/Screen-Recording-2022-04-01-at-7e936c6f0b38bac9237227432192d5e3e.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   
   [JavaScript Manual](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   
   Understanding and implementing the nested if statements (which contained the logic of the game) at the end of the code was a challenge. I first had to understand the logic diagram presented in the tutorial for the game.
   I did this by drawing my own logic diagram and comparing that to the the diagram in the tutorial. After this, the bigger challenge was translating that diagram into code. This was a challenge because the logic diagram
   did not tell me things like when to keep track of or increment certain variables or when to call certain functions. To account for this, I wrote down on my own logic diagram when to make certain function calls and when
   to track/increment variables. Now I had pseudocode. I converted that into code by doing two things. First, I looked at the javascript code I had already implemented to understand the syntax for things like if statements
   and for loops. Then, I looked at the javascript manual provided by mozilla (linked in the previous question) for the syntax/logic of specific things like incrementing variables. Because of this, I was succesfully able to
   complete the code for the logic of the game.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
    
    As a result of having made this project, 2 specific questions intrigue me. First, how does the window where the game is played know to scale to the user's display? When I was making the game, I could resize the preview panel freely and the elements of
    the game, such as the buttons for each tile, would resize/fit dynamically as I would increase or decrease the size of the window. Are there limits to this functionality, for example when the display of the user is too large or too big? Additionally,
     how could I have reduced the code such that I made the loadtime of the webpage shorter without compromising functionality? My code contained for loops and nested if statements, which can compromise runtime. If I were making a more complicated game,
     how would I ensure that it took the minimum amount of time to load properly? This is important because users do not want to wait to long for a game to load. Long load times can significantly decrease the traffic my game might get.
    

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   
   I would like to do a couple of things. First, I would add a counter that keeps track of how many times a user has won the game and how many times they have lost it. Having such a counter provides more incentive for players to succeed/compete at the game. 
   Moreover I would also add difficulty options to the game. This would make the game easy enough such that beginners can start playing, learn the ropes of the game, and get better at it, while also allowing a hard challenge for experienced players who want
   to test their skills. For example, the easy mode might contain only 3 buttons for the user to play the game with, whereas the hardest difficulty might contain 8 buttons as well as the computer cycling very quickly through the pattern each round.

## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/4ec04ad0567149fe9200b5698dac8d74)

## License

    Copyright [Abdulwasay Qureshi]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
