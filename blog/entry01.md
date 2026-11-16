# Entry 1
##### 11/15/26
## My Tool
I decided to develop a tower defense game for my freedom project, I will be working on the freedom project by myself. The game will work similarly to Bloons tower defense where when you place down a certain tower, you need to meet a certain threshold of cash in order to do so which challenges players to make important decisions on what to do that could put their entire game at risk. For making the tower defense game I decided to use [Kaboom](https://kaboomjs.com) The reason I chose this tool is because of the items that it offered in which resonated with me as they could help me build my game. Tools such as sprites, shooting, dialogue, obstacles, etc... all of these are useful for making my game. What I'm going to put in my game that makes it unique is that players don't just get to watch their towers battle but they can also combine different towers in which they can cause the individual towers to have combined passives and a whole new skill. ( I am planning on making at least 10 towers ) 

## Using Kaboom (Figuring out my tool)
This week, I've explored mostly the webpage of kaboom and tinkered inside of the page's code so I could understand what types of elements they offered for making a game by using their playground feature. During my tinkering I found out that they had a multitude of features that involved in changing the perspectives of the player, being able to emit audio through the screen, making the sprites interact-able almost like a rpg game, making game loading screens etc... I have mostly tinkered with their rpg section seeing how the speed works for the game and also how you could interact with the NPC inside of the [playground] (https://kaboomjs.com/play?example=rpg) :

``const speed = 1221 `` 

This was to set the movement speed for the sprite based on how high the number is  .

``const characters = {``
		``"a": {``
		``	sprite: "bag",``
		``	msg: "Hi Bean! You should get that key!",``
	``	},``
	``	"b": {``
		``	sprite: "ghosty",``
		``	msg: "Who are you? You can see me??",``
	``	},``
``	}``

For this line of code I understood that in order for the messages to function they needed to be called from the original sprite. A was given to the sprite in the first level in which when walked upon they will be given a set of dialogue through the messages. 

B was in the second level where it was the same thing as A, you walk up to him and he has a set of dialogue.


What confused me the most was the code they had in order to make the sprite go to a different level which was 

``	const levels = [``
		
			``"===|====",``
		``	"=      =",``
		``	"= $    =",``
		``	"=    a =",``
		``	"=      =",``
		``	"=   @  =",``
		``	"========",``
		``],``
		``[``
		``	"--------",``
		``	"-      -",``
		``	"-   $  -",``
		``	"|      -",``
		``	"-    b -",``
		``	"-  @   -",``
		``	"--------",``
		``],``
	``]``

  From My prior knowledge what I understand from the words A and B is that they are the variable of the sprites.
  On closer look I noticed that the code is similar to the level layout which the $ is the key and the @ is the spawn point given the player the = sign is the terrain of the map. From my observation this code is mostly about mapping your game, this will be most useful when I am thinking about what map I am going to assign for my tower defense game.


  ### Possible plans (EDP)
  From my current knowledge so far about kaboom I plan to use the sprites as the towers for my tower defense game and the = sign terrain as the 2d maps for my game, almost like a cool math game type of format. The messages however I won't make it function like the rpg instead throughout the level or waves of enemy I will push out short messages to give the players a short story line or tips of what is to come in the levels. Next week I am going to plug in the code so the Kaboom.js will be able to function in my code space after that I'll figure out health bars in the game and also a shooting mechanic which allows sprites to fire short beams or lasers at a target to do damage using the [shooter]((https://kaboomjs.com/play?example=shooter) playground. Right now from what I learned will help me understand the current format of how I can develop my map.


 ### Takeaways
 From the blog this week it helped me be able to figure out more diverse area of coding in my game which further expanded my recognition of behavioral patterns as I didn't understand the code where there were multiple dash and equal signs, but as I observed the code in kaboom, I am able to realize the similarities between them. As I learned more code from Kaboom it also strengthened my resolve to further continue my project knowing there is still a lot more things to learn ahead not in just coding but also in life as well. 



[Next](entry02.md)

[Home](../README.md)
