# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Hunter Nguyen

Time spent: 6 hours spent in total

Link to project: (insert your link here, should start with https://glitch.com/edit/#!/judicious-incongruous-soul)

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
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

//Start/Stop Button Toggles when clicked
![](http://g.recordit.co/iCveONVi3I.gif)
//The game has 5 functional game buttons that light up and play a sound.
![](http://g.recordit.co/GdKFrD2xQL.gif)
//Here is a lengthened version that highlights that the noises are playing at a 5 percent faster rate each turn, and that the user has three strikes
![](http://g.recordit.co/0dMWoX5tSi.gif)
//Full Winning Game
![](http://g.recordit.co/mNdFd31qbw.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
GeeksforGeeks.com and W3schools.com

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The greatest challenge I had while creating this submission was in the Javascript file and creating the controller for the game. The description and graphical representation provided by CodePath broke it down into small steps for me. However, I feel like a lot of the game was from CodePath's design and not my own, so it was challenging to decide how to even begin. Additionally, this is my first time using javascript and I am still learning about the capabilities and intricacies of the language. I found that javascript uses a lot of C++ syntax requirements such as semicolons and declarations. I overcame the challenge by using my resources that I listed above, and slowly broke up the problem into pieces based on the graphic provided. For example, the function guess is passed a buttom argument and the graphic asks me "Is guess correct?", so logically I used an if statement there. I continued on through each branch of the tree and eventually I figured out the solution. Another challenge for me was to have the pattern randomly generated. The javascript math library provided a randomly generated number between 0 and 1. This is not what I hoped out of it, as I wanted a random number generator that generates numbers in the range 1 to 5(I have 5 buttons). I eventually found my answer on GeeksforGeeks.com, however I quickly ran into a bug where the array was greater than 8 because I was puishing more and more random nubmers onto it. I used console.log to find out where I can reset the array and set the pattern = []. To briefly conclude, my biggest problems were with the controller for the game(guess function) and making randomly generated patterns for each new game.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
The primary question I have for web development after completing this is how I can add images to the buttons in the game. I researched a bit and there seemed to be a variety of ways outside of CSS. I could have done it in javascript and used document functions to make it interactive.  I was only able to upload pictures and put them on my website, but I was unable to properly align them. They were the same size as the buttons however, there was a noticeable amount of vertical space that ruined the alignment with the buttons. After toying around with margins and dimensions, I could not get it to move down the 50-100 pixels that it was higher than compared to the rest of the buttons in the row. I also want to know how powerful web development tools are. I think it was pretty amazing what three files could do. In college, I don’t really get to use html, css or javascript and the programs I write are much different. To reiterate, I want to know what are the limits of web development as this is my first introduction to it and it really surprised me.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on the project, I would have liked to be able to put the images inside the buttons and have them appear when pressed. The farthest I got in this problem was putting the images onto the web page but I struggled to make them interactive and hidden when the button was not being pressed. I also had issues with aligning the images to the buttons despite coding them to have the same dimensions. 

Another feature I would’ve liked to add was a more celebratory win and a more firm lost notification. Whenever my user won or lost, the webpage notified them with a pop up. I would’ve liked to fill the screen with fireworks or a cake for a win and an encouraging but taunting image or notifccation for a loss. I personally do not like pop ups so that is why I would want to remove them.




## Interview Recording URL Link

[My 5-minute Interview Recording]https://www.loom.com/share/959806429a09448899e7ed24fc45f37b)


## License

    Copyright Hunter Nguyen

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
