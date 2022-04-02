**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Joshua Lewis**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/edit/#!/mirage-radial-yak?path=script.js%3A7%3A21

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Winning the Game - Correctly repeated the computer's pattern
![](https://i.imgur.com/3rsEyfK.gif)

Losing the Game - Failed to correctly repeat the computer's pattern
![](https://i.imgur.com/lWM4UG0.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

   - rapidtables.com for colors
   - w3schools.com to get a better understanding of what the javascript was doing

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

   I am pretty new to Javascript, and when I tried to test the game for a moment I was confused as to why the buttons only lit up when I pressed them but not when the computer was playing clues. I looked through the Javascript to see if something was wrong there. Reviewing the instructions as well as looking at w3schools to better understand what is happening there all together, but especially inside of the functions like playSingleClue and playClueSequence. I circled back to the CSS and found that I should have just put the active #button.active pieces each under their corresponding button. I listed all of the buttons out then typed out the active elements separately. Fixing that mistake allowed me to see the button light up when the computer pressed them.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

   One thing I've wondered about web development is how the most popular, high-traffics are able to create updates to their website regularly and rarely interfere with the user's experience. When I go on websites such as YouTube and Netflix it is such a seamless experience and I'm fairly confident nothing will go wrong. It must be skilled developers on the other side.

   Also, I have heard of different Javascript frameworks such as React, Angular and Node (I think they are all frameworks)and I understand that a few are covered during this program. My question is how do developers know which ones are most worth their time learning. Do they serve different purposes or are they more or less interchangeable?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

   With some more time and familiarity with building in Javascript I probably would've completed the game with the option for extra buttons and a timer that got shorter with each round. I probably would have taken more time to complete change the style of the game.

## Interview Recording URL Link

https://www.loom.com/share/6574ef35db2642b8a67661fb6b8e1266

## License

    Copyright [Joshua Lewis]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
