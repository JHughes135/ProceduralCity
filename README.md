# GE1_Assignment
Games Engines 1 Assignment Proposal

For my Games Engines assignment I plan on procedurally generating a city containing a reasonable variation of buildings, streets and other objects that might be found in a city. 


## Why I chose this project
I have chosen this project because, for my Final Year Project I am creating a game with Unity. The game will be similar to Pacman but set in a 3D city environment where the player must avoid the rouge AI cars while completing objectives. For this I will need to generate streets for the cars to drive on and a city for the player to navigate. I thought it would be smart to take the opportunity to have my games engines assignment linked to my final year project. I also like the idea of creating semi-random environments to explore and see how changes in the code can affect their generation.


## How it works
My project creates a finite procedurally generated city. It works by creating a grid and assigning a value to each slot in the grid using Perlin noise. This value determines what building prefab is placed on that slot of the grid. Taller buildings and grssy areas are given a lesser chance of spawning to make it look more natural. This is done by altering the ranges at which each building is spawned depending on the number genreated. (I.e small building will be generated if number is less than 4. Where as a large building will be generated if number is between 8 and 10.) Streets are laid out in a grid like pattern between the buildings. The size of the city can be changed in the code.


## What I'm most proud of
The aspect of the project im most proud of is how natural the variety of the buildings and where theyre placed looks. Perlin noise and altering the chance of a building spawning depending on its size creates a city that seems to have smaller residential zones and larger skyscrapers grouped together.
