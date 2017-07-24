## Who am I?

I'm an engineer in Computer Science with a minor in Software Architecture, recently graduate from Polytech Nice-Sophia (2017 promotion).

Video game and game design lover, I'm currently searching a first job as a gameplay developer or a tool developer.

I think a good developer is someone who is passionate and creative, who has a team spirit, produce code that is maintenable,  upgradable, i.e. a comprehensive and readable code. Anyone can learn a programming language, but to know how to get back on something that has been produced to improve it, make a software component "beautiful", suggest an architecture to reach some properties expressing the pros and cons and decide together if it's the right solution, it's all of these things which allows to say "I am an Engineer".

If I want to join the video game industry, it's because I believe that it's the best medium to reach people's heart and bring them something. It can be joy, tears, personal thoughts or thought on another person, the player involvment is what that let them to live a mindful and unique moment.

## Video Game projects

### Eat Hat AR - Online turn-based strategy game in Augmented Reality - 2017 - School Project
_Final year project presented at the **"Festival International des Jeux de Cannes 2017"**._
![Eat Hat AR descriptive photo](/tom_site/eat_hat.png)
You can find a **video** of the project [here](https://www.youtube.com/watch?v=LyKAzMAzhVQ).

This project took us one semester, in parallel with our other courses. We were four developers (three of us with a minor in Software Architecture, and one in Human-Machine Interaction) and one 3D artist. EatHat AR is a turn based strategy game where the board is real AND virtual. You have a custom wooden board in the hand that you can move to see the different faces and know about the current game state. We add the real board around it thanks to augmented reality. The game is only playable online.
EatHat AR is a project to prove our competencies as engineer, so we design and develop the system in a way that it can scale with multiple game in parallel, it's easily maintenable by some other developer and it is customizable for a game designer without touching code but only using the Unity3D interface.

My work :
- Design and development of the data model (cubical representation of the board and movements of the pawns around it).
- Design and develop the client-server communication abstraction.
- Design and develop the service discovery in Go.

### ChessProject - Framework to prototype AR board game for Game Designers - 2016 - School Project
_End of the semester project_


![ChessProject descriptive photo](/tom_site/chessproject.png)


You can find a **video** of the project [here](https://www.youtube.com/watch?v=Hhxcq4Dgzz8).

During one month, I design with three developers and one 3D artist a framework prototype. Its goal is to provide to game designers the tools to create their own AR board game (chess-style) on a cubical board without writing a single line of code. Instead, they will work with Unity 3D with personalized field. As in Lego, you play with bricks : you plug some rule bricks (unity component) somewhere, fulfill the parameters and here we go the game is ready!

My work :
- Design and development of the data model (cubical representation of the board and movements of the pawns around it).
- Design and develop the "rule brick" concept : rules that launch events and that are triggered by anothers elements.

### Snowdon Racing - Arcade Car Racing - 2015 - School Project
_Project for the "Conception de Jeux Vidéo" course at Polytechnique Montréal during my exchange semester_


![Snowdon Racing picture](/tom_site/snowdon_racing.png)


For the Design Video Game coourse at Polytechnique Montréal, I design and develop with 3 other developers an arcade racing game. We use a basic race game skeleton provided by the teachers (car 3d md models, movements, and a Basic AI where provided). We added a radar, a jump (Rocket League-style, ie you can rotate the car midair), items to launch (Mario Kart-style with the green, red and blue tortoises), a nitro, destructible objects (a wall that hide some secret way to go faster), a respawn when you go out of the game, and signalisation on where to turn at the next bend.

My work :
- Design and develop attack objects in tortoise's mario kart-style (attack that goes right in front of the car and bounce on the wall, attack on the nearest car, attack on the car that is in first place)
- Design and develop object that can be destruct by using attack objects
- Help for the Level Design (shortway thanks to the destructible objects, limits of the map)
- Develop the final ranking and the restart of the game

### Rogue Shield - Rogue Like "The best defense is a very good defense" - 2015 - Personal Project
_Personal project during my exchange semester at Polytechnique Montréal_


You can find a **video** of the project [here](https://www.youtube.com/watch?v=5zhBV104Mas).


With a three developer team, we design a Rogue-Lite where the particularity is that the only way to fight is to use our magical shield that doesn't do any damage. The player need to repulse the different projectiles right into the enemies to kill them, or to repulse them directly and use your environment full of traps to kill them.
This game is in 2D with a side scrolling (as in Rogue Legacy) : you'll need to travel around the procedurally generated level to reach the final room.

My work :
- Develop character movements
- Develop the shield gameplay (repulse enemies and projectiles from them or from traps)
- Develop an inventory, enemy looting, and item use.
- Develop triggers traps (as dart trap that are activated when the players is in front of it)

### Support or Contact

If you have any question about my projects or if you just want to talk with me, send me an e-mail at dallagnol.tom@gmail.com! This github page only contains the video games I've developed, but I have plenty of others projects I've done during my engineering school, either personal projects or school projects! Do not hesitate to contact me to talk about all of them.

You can reach me on Linkedin too at https://www.linkedin.com/in/dallagnoltom/ .
