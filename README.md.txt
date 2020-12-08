Ultimate Frisbee

Ethan Judkins, Section 02
Ben Kamide, Section 01
Vince DeHoratus, Section 07 

Here’s our video! Check out the comments https://www.youtube.com/watch?v=7JB5IR4GGIM 

General Overview: 
	
We used the pong code as the basic framework for our game when we began constructing Ultimate Frisbee. The alterations come throughout the code, mostly in the main.lua file but also in the paddle and ball files. Note that although still titled “paddle” and “ball”, the files correspond to the player and the disc respectively. The point of the game has changed from trying to beat the other player to a collaborative game between either the two players, or the user and the AI. 

Difficulties we faced:

Most of the design changes, such as the green background, field markings, and Temple logo were simple in concept, but offered challenges in their execution. Separate designs had to be made for the disc, the players, the logo, and the endzone and field lines. The process of figuring out the x and y coordinates for each of the lines on the screen was strenuous, but eventually each aspect of décor was placed in the correct spot. 

In one case, the difficulty surrounding the design of the players made the hit box of the disc on the players a little off, with the box stopping about halfway up the players’ head. To resolve this while adding some character to the design of the game, we wrote a hint to the bottom of the screen that advised players to catch with their body instead of their heads. 

It was also difficult to figure out the scoring of the game. We were originally going to have a clock that timed the length of each run, but we decided that points were a better way to go, and we could configure several aspects of the points system to be more enjoyable, like having sound effects for a loss and a new high score. The actual coding of the scoreboard itself was difficult to determine and work out, but after thinking through it logically we were able to add a couple of if and else statements to add the function.

The largest difficulty we faced was with the issue of adding defenders. We managed to program random defenders to appear and block the ball as the game went on, but in practice, the defenders would disrupt the game too much and make it too difficult to play, so they were removed. 

In deciding to go forward without defenders, we made the choice to focus on the feel and aesthetics of the game to enhance the player’s experience, which was when we began to add the different design elements like the field décor. We ran into several obstacles with these changes. An idea was to include large text on each of the endzones, but we couldn’t figure out how to rotate text or change the font, as downloaded fonts would end up too pixilated. To compensate for this, we added a Temple logo to make the field feel more personal for Temple students and players. 


What we enjoyed:

It was fun to work together on a project we could all relate to; we had all met before playing on Temple’s Ultimate Frisbee team, but this project allowed us to collaborate in different ways than we do on the field. 

The most enjoyable aspect of the game creation were the small details we added at the end. After determining the object of the game and coding in the points system, we were able to focus on small aesthetic details that would ultimately contribute to the overall feel of the game. While meticulously testing different coordinates and spacing of the players and logos and designs was frustrating during the process, the final product was worth it. We even took a step forward, adding the noises of real frisbee catches and bounces to enhance the experience, as well as cheers and awws in response to player performance. The background music was just for fun, but we think it adds a nice touch. 














*note: the background music file was too large to add to github, so it was submitted to canvas instead. You can hear it during the video at parts*
