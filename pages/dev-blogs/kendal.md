---
layout: page
show_meta: false
title: "Kendal Mitchell Dev Blogs"
subheadline: "Weekly Dev Blog Updates from Kendal!"
teaser: "Weekly updates and screenshots are documented here"
header: 
    image_fullwidth: "momentum_banner_970x321.png"
permalink: "/dev-blogs/kendal/"
---
## Welcome to Kendal Mitchell's Personal Production Journal

### Week 2
Kendal Mitchell, PPJ 1

Tasks Done: 

This week I worked on testing a variety of solutions to 

* Create our 5x5 hex gridboard
* Allow player movement. 

Initially, I was working with Unity's hexagonal grid and tile palette, 
we eventually shifted over to displaying hexagonal models made with ProBuilder to ease our efforts later down the road for procedurally generating maps.
I researched the A* algorithm for pathfinding and assisted in paired programming for our technical demo. Additionally, I also

* Created a main menu for the game

Overall, I spent about 4 hours researching and 2 in development.

Positive:

We were able to nicely divide our team into roles of designers, programmers, and artists. The team was also eager to coordinate and share ideas with one other.

Negative: 

We ran into some issues getting everyone access to files with SourceTree, but found alternatives with GitHub Desktop and GitKraken.

Upcoming:

We'll be further delegating tasks as we go deeper into development.

### Week 3

Kendal Mitchell, PPJ 2

Tasks Done: 

This week I worked with the others creating our HexMap (grid) and tile scripts. 

* Setup a system to generate Hexagonal grids with adjustable rows, columns, and spacing
* Built public interfaces for the HexMap and Tile GameObjects.
* Designers can now input HexType variants through the Unity Editor rather than through scripts.

Our generated HexMaps utilize an "odd-r" horizontal layout. This orientation isn't set in stone at this point but I ended up learning how to adjust it as I learned how to generate it.

Overall, I spent about 6 to 7 hours in development.

Positive:

Core components! Map creation has been automated and we can now track information not only for the Hex Tiles, but the HexMap itself too. Our artists are pumping out enemy designs and it's exciting to see so much progress over a short amount of time.

Negative: 

I was having some trouble line drawing and calculating distances for hexes but with some research found that Bresenham's algorithm may be a potential solution. It is possible that it may be hampered by our use of offsets, but this is still TBD. If necessary, our HexMap will likely need to change from a square offset tile grid to one using axial coordinates. 

Upcoming:

We're hopefully getting to the point now where we can start integrating pathfinding and player/enemy units types. I also had time to start prepping utility functions for pathfinding as well.

### Week 4

Kendal Mitchell, PPJ 3

Tasks Done: 

This week I worked with the others in setting up pathfinding and hex distance calculation. 

* Refactored HexGrid generation to produce a hexagonally shaped grid
* Setup functions for hex grid calculations and path recognition
* Converted from our offset coordinates to axial/cube for hex calculations

Just as planned, our conversion from offset coordinates to axial went smoothly, saving us a lot of time and allowing us to focus on hex coordinate math.

Overall, I spent about 7 to 8 hours in development.

Positive:

We saw a lot of growth in creating enemy assets and even got started on UI elements. We had a great design meeting in which we got to flesh out a lot of how we wanted the game to work too.

Negative: 

We ran into some issues with our previous data structure utilized for storing the Hex game objects but were able to find an improvement and get things working smoothly. 

Upcoming:

We should be getting to focus on intensely on enemy AI and creating player abilities.

### Week 5

Kendal Mitchell, PPJ 4

Tasks Done: 

This week I worked with the others in integrating our new hexmap with our player, enemy, and game controllers. 

* Constructed HexMap and refined coordinate system 
* Adjusted LevelGeneration script for a HexMap
* Pair programmed with other team members to translate HexBattleController and movement scripts to utilize cubic coordinates


Overall, I spent about 8 hours in development.

Positive:

Implementation of UI, hexgrid, and player movement together.  

Negative: 

We ran into setbacks getting highlighting and the momentum movement components working but were ultimately able to get it implemented. 

Upcoming:

Refactoring codebase for organization and brevity. Implementing EnemyAI and hex/enemy variants.

### Week 6

Kendal Mitchell, PPJ 5

This week, my time was spent with changing our process for generating visuals on the map.

* Refactoring HexGrid Map Visual HexPrefab Placement
* Utilizing Unity's Scriptable Objects for HexSettings
* Setting up a LevelCreator for the designers

Overall, I spent about 7 hours in development.

Positive:
Unity's Scriptable Object system was very easy to work with and the process of adding the objects onto our current Hexes is going smoothly.

Negative:
I did have to spend some time learning how to use the Scriptable Object system and had to spend additional time refactoring our older code.

Upcoming:
Fleshing out other hex variants and finishing ingame background music and a main menu theme.

### Week 7

Kendal Mitchell, PPJ 6

This week, my time was split between creating new types of status effect hexes and creating music for the game. 

* Setup a function to edit and create and assign a Hex's settings on our map.
* Created several types of hexes for the player to interact with.
* Produced several theme loops for our Main Menu and Battle Themes.

Overall, I spent five hours programming and three hours making music.

Positive:
I ended up finishing music in time for our first trailer and the new Hex variants added more depth to our gameplay loop. It's been fascinating seeing all the different components of our game come together. We're finally getting our art assets integrated in too.

Negative:
I didn't have time to make positioning hex variants on the map accessible in a non-programmatic way. Getting to finish this would help our designers to finish levels more quickly.

Upcoming:
In addition to creating more music and SFX, I need to work on creating a frontend editor for assigning different Hexes at certain positions.


### Week 8

Kendal Mitchell, PPJ 7

This week, in addition to continuing work on music/SFX, I created a frontend level editor and pair programmed on our EnemyAI.

* Setup a frontend level editor for place varying hex types and boundary hexes.
* Pair Programmed on Enemy AI with Yash
* Started making background tracks with heightened tempos 

Overall, I spent about 7 hours in development.

Positive:
I was able to get a level editor setup for our designers, make more music, and help debug enemy AI.

Negative:
Ran into an issue where many of our materials begun linking to materials that were pink. It ended up being an issue resulting from us not starting our project with a "Universal Project Template". I got this fixed, but it did take up some time.

Upcoming:
I'll be working on finalizing music/SFX and completing work on our enemy AI ability and logic variations.

### Week 9

### Week 10

[back](https://yashpand3y.github.io/dev-blogs/)