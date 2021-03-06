---
layout: page
show_meta: false
title: "Yash Pandey Dev Blogs"
subheadline: "Weekly Dev Blog Updates from Yash!"
teaser: "Weekly updates and screenshots are documented here"
header: 
    image_fullwidth: "momentum_banner_970x321.png"
permalink: "/dev-blogs/yash/"
---
## Welcome to Yash Pandey's Personal Production Journal

### Week 2
Yash Pandey PPJ 1

Tasks – Hours taken:
-	Infrastructure Set-up (Unity Hub, get correct unity version, set-up github)
o	1.5 Hours
-	Tech Demo (Pair Programming with Tech Demo Team, grid initialized, movement foundation laid, environment design)
o	1 Hour
Total Hours: 2.5 Hours

Positive: Were able to tackle some design questions and create the tech demo

Negative: The team’s schedule is very tight making it hard to meet up for meetings

Upcoming: Game Mechanics Design, Player Movement (and all the arithmetic related to it), Learn about Algorithm A* for figuring out AI mechanics


![image](https://user-images.githubusercontent.com/39490762/114806322-8fd70c80-9d72-11eb-8a57-ea4659fd6558.png)
![image](https://user-images.githubusercontent.com/39490762/114806339-9796b100-9d72-11eb-99a5-a5e611054354.png)
![image](https://user-images.githubusercontent.com/39490762/114806345-99607480-9d72-11eb-8890-702de08b7aa3.png)

### Week 3
Yash Pandey, PPJ 2
Tasks – Hours taken:
-	Hex object with implementation of grid calculation references, grid generation script.
o	3.5 Hours
-	Standardized Hex Template using classes for laying the foundation for map generation (level design tool creation)
o	2.5 Hours
Total Hours: 6 Hours

Positive: Constructed Hex Class with future proofing for level generation, hex distance (between two points) and movement calculation trackers, etc. Also helped implementing the hex grid generation for creating the hex map

Negative: Difference in purpose for elements give rise to the need for further specification and discussion on details

Upcoming: Unit Movement, Unit Path Choosing (how to get from point A to point B)



![image](https://user-images.githubusercontent.com/39490762/115772490-2d3acd80-a37d-11eb-9a70-d568f68a69f5.png)

### Week 4
Yash Pandey, PPJ 4
Tasks - Hours Taken:
- Highlight Hex function (along with refactoring and improving several structures)
o 5 Hours
- Integration of path decision between two points
o 2 Hours
- Creation of Mathematical Algorithms for Hex-based calculations
o 0.5 Hours
Total Hours: 7.5 Hours

Positive: Implementation of Hex Highlighting and modifications to Hex object for better clarification and build

Negative: Implementation, refactoring, and silly mistakes caused tasks to take a whole lot longer than expected. 

Upcoming: 
- Finishing of implementation of Hex movement
- Unit (player and enemy) generation and implementation to complete Game Loop
- Perhaps even taking a look at Map Generation to allow for a custom bias in the tiles that get used.

Screenshots:


![image](https://user-images.githubusercontent.com/50269613/116589116-4e09a280-a8ea-11eb-923d-2afcaa826eb0.png)


![image](https://user-images.githubusercontent.com/50269613/116589718-edc73080-a8ea-11eb-83a9-fd8bdde51ef9.png)

### Week 5
Yash Pandey, PPJ 5
Tasks - Hours Taken:
- Helped with Conical Highlight Function
o 1 Hour
- Helped Hex Implementation from Grid
o 2 Hours
- Resolved Merge Conflicts
o 1 Hour
- Generate algorithm for figuring out direction of momentum
o 1 Hour
Total Hours: 5 Hours

Positive: Lots (and lots) of Pair Programming, Resolved Merge Conflict, Translated Square Grid to Hex

Negative: Merge Conflicts, Realize need to clean pipeline and code, Tasks were only partially complete

Upcoming: 
- Refactor and Clean up Code
- Implement algorithm for finding direction of momentum
- Implement Enemy AI (while following rules of Movement)
- Integrate different art and tile assets created (create tile bias, enemy bias, etc.)


![image](https://user-images.githubusercontent.com/50269613/117350646-cdfbb380-ae7a-11eb-86d6-84e567c0bf9b.png)
![image](https://user-images.githubusercontent.com/50269613/117351136-5b3f0800-ae7b-11eb-93a1-4389458d45e3.png)
![image](https://user-images.githubusercontent.com/50269613/117351241-7873d680-ae7b-11eb-8be0-809729e8ce1b.png)

### Week 6

Yash Pandey, PPJ 6
Tasks - Hours Taken:
- Create Algorithm for Hex Grid Graph Generation
o 7 Hour
- Implement Dijkstra's Algorithm to return list of tiles to traverse to get from point A to point B
o 3 Hours

Total Hours: 10 Hours

Positive: Robust and thoughtful implementation of Graph, Dijkstra's, and integration

Negative: Graph Implementation Edge cases took time because of tedious edge case errors

Upcoming: 
- Refactor and Clean up Code
- Finish Enemy AI implementation

![image](https://user-images.githubusercontent.com/50269613/118175899-b2eeed80-b3fe-11eb-8c13-b774f8e5654b.png)

![image](https://user-images.githubusercontent.com/50269613/118175923-bda98280-b3fe-11eb-8953-78d7b1a3dd9b.png)


### Week 7

##Yash Pandey, PPJ 7
Tasks - Hours Taken:
- Implement Dijkstra's GraphSearch 
o 2.5 Hours  

- Debug graph creation (memory references) (Unity doesn’t like me debugging self-referential structures </3) 
o 6 Hours  

- Clean up and reformat functions for robustness, clarity, and better functionality 
o 2 hours  


Total Hours: 10.5 Hours

Positive: Correct major issues with graph creation (offsets, co-ord patterns)

Negative: Graph Implementation Edge cases took time because of tedious edge case errors

Upcoming: 
- Finish Enemy AI implementation
- Figure out why `graph[q,r,s].Neighbours.add(graphh[q, r+1, s-1])` doesn't work


![image](https://user-images.githubusercontent.com/50269613/119035513-a548e300-b97d-11eb-959e-f95f48118e06.png)
![image](https://user-images.githubusercontent.com/50269613/119035612-c01b5780-b97d-11eb-8121-588910cef5e0.png)



### Week 8
##Yash Pandey, PPJ 8
Tasks - Hours Taken:
- Finish Pathfinding
o 3 Hours  

- Integration
o 5 Hours  
Total Hours: 8 Hours

Positive: Updated pathfinding to path around obstacles (set distance to occupied nodes as infinity)

Negative: Integration of pathfinding was 

Upcoming: 
- Finish Enemy AI integration
- Create different attack sequence behaviour for enemy behaviour variety 


![image](https://user-images.githubusercontent.com/50269613/119882521-81951800-befc-11eb-8708-c77ad96a461d.png)
![image](https://user-images.githubusercontent.com/50269613/119882554-8c4fad00-befc-11eb-9ba4-4e78bd0f314e.png)

### Week 9

### Week 10

[back](https://yashpand3y.github.io/dev-blogs/)