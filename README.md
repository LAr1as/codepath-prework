# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Luisa Arias

Time spent: 8.5 hours spent in total

Link to project: https://glitch.com/edit/#!/classy-tattered-collision
Live site: https://classy-tattered-collision.glitch.me

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

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Losing the game:
![](https://i.imgur.com/uiNZfCg.gif)

Winning the game:
![](https://i.imgur.com/HLS4pQv.gif)

Different patterns:
![](https://i.imgur.com/2oofglq.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

"stackoverflow" to learn how to generate random integers, "JavaScript: Creating Sounds with AudioContext" to create different tones for the buttons, "rapidtables: css color codes" to change the aesthetic of my project, and "w3schools: CSS Web Safe Fonts" to change the font of my project. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
 
Although I had fun creating the light and sound memory game, I did come across some obstacles. One of the obstacles was getting to learn how to use glitch and the tools it offered. I have never used Glitch before, so having to create a project was a little confusing. I accidentally created two projects without even realizing, but then I decided to watch an introduction to Glitch video. The video helped me understand what Glitch was a bit better. After that I realized that I had created two new empty projects. Another challenge that I faced was with the coding project itself. I had completed the basic requirements but I wanted to give it a try at the optional features. The hardest feature for me was to generate a random pattern. For this, I had to use outside resources to learn more about Math.random() and how to use it. I watched some videos that explained what Math.random() did and how it could be used. Then I did some research on how to make it produce an array of 9 random numbers from 1-5. However, trying to implement the array with the code I already had was difficult. At first it would not work and I tried doing different things with the array, like assigning it to a variable or creating a separate function, but nothing would work. Finally, I decided I needed to abandon the array and try using a function only. With a little more research about generating a random 9-digit pattern, I came across stackoverflow where I found the answer I needed. Someone had posted the question “how to implement random pattern Javascript,” under this a comment gave an example of how to generate the pattern so I used their idea and added it to my project. This time everything worked and my project was making a random pattern.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
 
I have made a few very simple websites and other coding projects before, and I have always wondered how web developers deal with bugs? I always hear how people complain about bugs and how long it takes them to find them and fix them. My question can be expanded into more specific questions like what exactly is a bug? How do you identify a bug? Can your project still work even if it contains a bug? Can there be multiple bugs? Can a bug go unnoticed for a while? Is there a strategy to prevent bugs? I would like to learn more about how to deal with bugs and other errors that affect your code so I can be prepared for my future career. I am a person who likes problem solving challenges, but sometimes I don’t even know where to begin looking. For example, when I was creating my project, I did a test run but none of my buttons were working. I tried testing it again but it still wasn’t working. Then I looked over the code but I could not find any errors. Finally I gave up trying to fix it for that day and decided I would continue the next morning. When I opened my project again, I tested it and all of the sudden it was working again. I wasn’t sure what had happened or how it got fixed. Maybe there was a bug and my code was not being read right. This got me thinking about all the bugs that could go unnoticed with larger and important projects.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
 
If I had more time to work on this project I would definitely try to add more features. One of the things that I wanted to add was the strikes count. I wanted to give the used 3 tries to get the correct pattern before the game ended. I know this would have taken me a few hours or more to make it work with my code since I would need to do some research on how to add the strike count. Another thing I would have done is make the layout of the button nicer, like put the start/stop button at the center instead. I would also want to spend time decorating the background with some images or figures so it wouldn’t look too simple and it would draw attention.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Luisa Arias]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
