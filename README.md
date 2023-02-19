# Get_Wasted_H4H
An RPG revolving aimed to teach proper waste disposal 
and sorting in a fun and interactive way.

## Inspiration
According to The World Bank, the world generates about 
2.01 billion tonnes of municipal solid waste, of which 
at least one-third is not processed in a way that promotes 
sustainability. Moreover, high-income countries contribute 
to about one-third of the world's total waste. Looking to 
the future, it is predicted that global waste will grow. 
In order to keep Earth sustainable, we have to improve the 
ways we process waste.

Energy and resources are used to produce, process, transport, 
prepare, store, and dispose of waste. When it is not possible 
to properly handle waste, these materials are typically deposited
in a landfill. Furthermore, not all materials and products can 
be reused or recycled. Currently, in California, there is a 
reduction in waste and recycling. Although many places implement
a disposal system where we can sort our waste, these efforts
may not be enough to keep Earth sustainable for future generations.

## What it does
Our game is a simple fighting RPG. Using WASD to move around the
world, players can run and avoid various enemy Recyclies, Trashies,
and Composties. Press 'J' to fight enemies on the left, and press 
'K' to fight enemies on the right. Once enemies are defeated, players
collect the sortable items and drop them off at the corresponding 
bins where they should be properly disposed of. If the player sorts 
the waste correctly, their score increases. If the player sorts the
waste incorrectly, their score decreases but the game doesn't end. 
The game only ends when the player loses all of their health from 
the enemy waste monsters.

## How we built it
When we started this Hackathon, we had no idea what we wanted to 
create. We spent a couple of hours brainstorming and researching 
various social good topics, eventually settling on a game related
to proper waste disposal. Initially, we wanted to make a Roblox game
that focused on teaching kids how to sort trash, recyclable items,
and food waste. However, we later decided to change our project and 
make a RPG fighting game, since we felt that the change would help 
our project be more interactive and fun to play. 

To make our final project, we used Unity, a cross-platform game engine,
writing our code in C#. Most of us were unfamiliar with C#, so this
project was a huge learning experience for us. We drew our animations 
and most of our game sprites in Procreate, a digital art application.
In order to work on the code together, we used CollabCode to share functions. 
We wanted to incorporate math concepts into our project as well, so we researched 
kinematics formulas, specifically involving drag and air resistance, to properly
model object interactions in our game. Then, we implemented the math by writing 
functions to determine the position of an object as well as its direction and velocity.

## Challenges we ran into
One of the bigger challenges we faced was when we set out to add physics to 
our mobs when they are knocked back. We didn't just want to put a simple 
parabolic arch to our mob arch. We wanted it to be _realistic_ as our character
beats off raging banana peels. We looked into projective flight and were
able to implement air resistance in the trajectory of our flying plastic cups. 

It was a struggle to understand the physics of our game when interpreting 
it from a two-dimensional space into a three-dimensional one. Because we 
decided that the monster is airborne after being hit, it was also a struggle
to figure out exactly how many variables would be constantly changing due 
to the varying forces. After properly deriving acceleration and the velocity
of the cups, we were able to represent the movement in both an x and y-component.
We then were able to apply these xy-components to our flat world by scaling 
vectors to show movement for our turbulent trash.

## Accomplishments that we're proud of
We programmed a functional video game with our own animations! Our project
is not only a fun fighting RPG, but it is also an educational tool that can 
teach young kids how to properly sort waste. Since this was the first time 
for most of our team to be working in C# and with Unity, we're proud of the
new skills that we are able to take away from this experience.

## What we learned
During the brainstorming and research part of our project development,
we learned more about the different ways that waste is processed, what 
specific steps the materials go through, and what kinds of materials can 
be recycled, composted, or thrown away. Once we started designing our game, 
we enjoyed becoming familiar with Procreate to make our sprites and animations. 
We were able to explore design principles and game design ideas. Through 
some struggles, we learned how to implement 2D game physics. Lastly, we all 
gained more knowledge on how to program in C# and Unity.

## What's next for Get Wasted
The project can be expanded by adding more gameplay elements. We could 
include more new enemies to make it more challenging for players to determine
how to sort waste. Like most games, this project could be built further to 
have a wave system, boss stages, and/or different levels gradually increasing
in difficulty. We had ideas to include power-ups and character customization 
options too. Other improvements include better graphics, improving our 
animations, and making a more consistent art style with all elements of our 
game. Most importantly, we want to include more informational blurbs to make 
our project more educational. We believe that our work has the potential to 
make waste disposal education fun, which will hopefully effectively teach our
players and encourage them to be more mindful of their waste disposal habits.
W Sustainability!
