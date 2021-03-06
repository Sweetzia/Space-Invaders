Corona Invaders Game
---------------------------------------
**Interactive-frontend-project - Marjolein van Leeuwen**

This is my Interactive Front-end Development project. I created my own Corona Invaders game which is based on the original game of Space Invaders, created by Tomohiro Nishikado in 1978. 
And I got inspired bij the [#JavaScriptGames][0] from developer Ania Kubów. 

Click [here][DEMO] for my deployed project.

![SPACE INVADERS demo](assets/images/game.gif)

**User stories**

* As a user : As a new visitor to the game I want the page to be easily navigated.
* As a user: As a new visitor I want clear instructions on how to play the game.
* As a user: I want a game that responds quickly to my interaction.
* As a User: I want a game that is fun and exciting to play

The ideal user:
* Age 6+
* Children and adults


**Strategy**

* My Goal is to design a Corona Invaders game that is fun and easy for users to play. 
The page will be simplistic and easy to navigate around. Its purpose is to make the user happy and strengthen spacial skills.

**Scope**

This page is to provide users with quick access to the Corona Invaders game. The Game is to challenge the users to defeat the Corona Invaders.

**How to play**

Press the "Play Corona Invaders" button and the game container will appear. 
Wait for the game to begin. The user can see his/her blue spaceship and the Corona Invaders coming down and move from left to right.
The challenge is to shoot all Corona Invaders with your lasers, before they hit your spaceship or reach the end of your grid.

If you press "How to play" you will get a short tutorial about the game and which keys you need to use to play the game.

**Structure**

* The game buttons are displayed on a black galaxy background. 
* Two options are presented to the user, “Play Corona Invaders” and “How to Play”. 
* The pink Corona invaders and a blue spaceship appear. 
* You can move the blue spaceship, by pressing the left arrow and right arrow on your keyboard
* By pressing the space key you can shoot green lasers to the Corona invaders.
* When you defeat all 30 pink Corona Invaders, “YOU WIN!” 
* When the Corona Invaders reach your spaceship or reach the end of your grid its "GAME OVER".


**Skeleton** 

I created a wireframe using the program “Mockflow”. 

![Wireframe](assets/images/Mockup%20wireframe.png)

**Surface**

* For the surface plane I wanted the design to set in space. 
* My background design was inspired by the Galaxy.
* I used space assets and corona cartoons in my game

**Technologies**

1. HTML
2. CSS
3. Javascript

**Features**

* Game Menu buttons. The game menu reveals itself with two colourful menu buttons. When the user selects the "start Corona Invaders" and "how to play" button you notice a hover glow effect. 
When you get redirected to the Corona Invaders game page & how to play page, you can leave this page by pressing the EXIT button.
The hover glow effect buttons were styled with the css code. 

* Scoreboard and result at the top of the game page

* Audio and music from the website: [classing gaming.][a] You hear exciting Space Invaders music in the background when you play the game and Space Invaders sounds when you succesfully [hit the Corona Invaders][b] with your laser, when [YOU WIN][c] the game and when its [GAME OVER][d]. 

**Testing**

All testing carried out was done manually.
Testing problems I encountered:

* My corona Invaders did not move and I could not shoot my lasers with my spaceship. 
After feedback from my mentor I decided to start over with my Corona Invaders code, because I did not really understood some of the code from [Coding Dojo][5]. 
I watched a different tutorial from developer [Ania Kubów][0], which made me understand the JS code more on how to make a grid for the game and for example how const,functions, if/else statements and keyCodes worked in your code. 

* I could not succeed in adding audio to my game. Until I learned how to add and load audio in your JS file through the youtube tutorial from [code explained][8]. 

* In my JS code on line 30 I encountered an "Uncaught TypeError: Cannot read property 'classList' of undefined". I was not able to fix this TypeError. 

**Features Left to Implement**

* Implement mobile controls in my game, so you can play Corona Invaders on a mobile touch-enabled device.
* Adding more difficulty levels and different coloured Corona Ivaders to defeat with your spaceship.

**Deployment**

This project was developed using GitHub.

I followed the next steps to deploy my game on the GitHub pages:

* Log into GitHub.
* Select Sweetzia/Space-Invaders in the repository list.
* Go to Settings
* Scroll down to the GitHub Pages section.
* Select the Master Branch
* On selecting Master Branch the page is automatically refreshed, the game is deployed.
* The link can be retrieved to the deployed website.

**Credits**

* Media: I downloaded space assets on the website [kenney.com][1] ( a free game assets website).
* I downloaded Corona virus microbes images from [pngtree.com][2]
* Audio and music from the website: [classing gaming.][a]

**Acknowledgements**

*I got inspiration from:*
* The original [Space Invaders game][3]
* Desktop mouse and keyboard controls on the website [MDN web docs][4]
* Code from the youtube tutorial from [Coding Dojo][5] about “ how to build a Space Invaders Game using only HTML, CSS & Javascript
* Code from the youtoube tutorial from a developer named [Ania Kubów][6] : "Space Invaders in JavaScript, HTML and CSS Walkthrough!"
* Code from [codepen.io][7] to add a glowing hover effect to my game menu buttons.
* Audio JS code from the youtoube tutorial from [code explained][8]: "Code The Snake Game Using JavaScript and HTML5"

***I want to thank my mentor Brian Macharia for guiding me through the process of creating my own game inspired by Space Invaders.***


[a]: <https://www.classicgaming.cc/classics/space-invaders/sounds>
[b]: <https://www.classicgaming.cc/classics/space-invaders/sounds>
[c]: <https://instrumentalfx.co/kids-cheering-sound-effect/>
[d]: <https://www.classicgaming.cc/classics/space-invaders/sounds>

[DEMO]: <https://sweetzia.github.io/Corona-Invaders/index.html>
[0]: <https://www.youtube.com/channel/UC5DNytAJ6_FISueUfzZCVsw>
[1]: <https://kenney.nl/>
[2]: <https://pngtree.com/freepng/hand-drawn-cartoon-bacteria-virus-microbe-corona-virus-image_5334155.html>
[3]: <https://nl.wikipedia.org/wiki/Space_Invaders>
[4]: <https://developer.mozilla.org/en-US/docs/Games/Techniques/Control_mechanisms/Desktop_with_mouse_and_keyboard>
[5]: <https://www.youtube.com/watch?v=XmqAPQsc1n4&t=3465s>
[6]: <https://www.youtube.com/watch?v=kSt2_YZzCec>
[7]: <https://codepen.io/kocsten/pen/rggjXp>
[8]: <https://www.youtube.com/watch?v=9TcU2C1AACw>
