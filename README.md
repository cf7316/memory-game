# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Samantha Liu**

Time spent: **4** hours spent in total

Link to project: (insert your link here, should start with https://github.com/cf7316/memory-game)

## Required Functionality

The following **required** functionality is complete:

* [y] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [y] "Start" button toggles between "Start" and "Stop" when clicked. 
* [y] Game buttons each light up and play a sound when clicked. 
* [y] Computer plays back sequence of clues including sound and visual cue for each button
* [y] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [y] User wins the game after guessing a complete pattern
* [y] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [y] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [y] Buttons use a pitch (frequency) other than the ones in the tutorial (Ukulele pitches!)
* [n] More than 4 functional game buttons
* [n] Playback speeds up on each turn
* [y] Computer picks a different pattern each time the game is played
* [y] Player only loses after 3 mistakes (instead of on the first mistake)
* [n] Game button appearance change goes beyond color (e.g. add an image)
* [n] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [n] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:
When the user wins, the game plays a 4-note C chord ukulele-style.

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

    I could not load the glitch webpage, so I worked on the project from an imported github project by another user (https://github.com/potch). To the best of my knowledge, what I imported is identical to the template on glitch and the rest has been my original work.
    
    I used the following page to learn about how to generate random numbers in javascript: https://stackoverflow.com/questions/4959975/generate-random-number-between-two-numbers-in-javascript
    
    I used this link to fix the audio-playing problem that comes with google Chrome: https://developers.google.com/web/updates/2017/09/autoplay-policy-changes#webaudio

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    I found out about CodePath two days before the application deadline, so I had little time to work on the project. In particular, the glitch website would not load when I started the project. This surprised me but I was not daunted by the challenge the challenge. I first emailed the admin of CodePath to inform them of this issue. Then, with my previous knowledge of github, I imported a project template and completed the project without glitch. Although I did not have the opportunity to see what has changed as soon as I wrote the code, I studied the guidelines rigorously. Afterwards, I ran the program locally and solved the minor problems of setting the script and using resume() to allow my Google Chrome to play the audio. This is why my recording and gif are on my google chrome, and I am sorry about the confusing.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

    The ability of a webpage to interact with the users fascinates me. This project introduced me to the basic ideas behind what I am so used to doing-- interacting with my computer. I would like to learn more about what actions users can perform because this has an enormous range of implications in programs and games.
Another question I have is about live and multiplayer games. I know that this would entail much more information about the internet, but the inclusion of more players would open up new dimensions for this game. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

    I have been playing an instrument since I was little and the set-up of this game reminds me of the perfect pitch training/testing app that would be useful to many music students. With 12 buttons to represent each note and generating notes randomly each turn, I could turn this game into that app. The user would hear a tone and choose what note they think it is. The same idea could be extended to chords (which is an app that I would personally use because I do not have chord-identifying skills). It would even be possible to make a simple instrument from this game, and the user could interact with the keyboard instead of the mouse for easier controls. In general, I found javascript to be flexible and powerful through this project.



## License

    Copyright [Samantha Liu]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
