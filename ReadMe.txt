T01_G01
Igor Liberato de Castro
Lucas Borborema Nakajima
PROGRAM DEVELOPMENT STATE:
We were indeed able to implement all the required features, not just relating to the game itself but also the menu and leaderboard 
features are present and working as expected.
MAIN DIFFICULTIES:
The development process went quite well, with few setbacks. The initial stages of development proved to be perhaps 
the most difficult, as we were still getting used to using the C++ language in game development. From the start we decided to use a 
strictly functional approach in almost all stages of the program, creating many separate functions that are each responsible for 
a specific area of the game. In this way we kept our code as organized, approachable and easy to work with as we could, therefore 
almost eliminating the amount of setbacks we had due to simple misplacements (which we had, in previous personal projects ,
had problems with when using non-functional programming). The only major  problem of such type we had happened at the very final 
stages of programming, while doing the leaderboard, the cause of which we were eventually able to notice by ourselves. The function 
to move the robots also proved to be particularly challanging, specifically moving them in the same order every iteration
(which we solved by making a vector of vectors containing the x and y coordinates of each robot in an order determined by their 
original placement) and determining the fastest path to take to reach the player (which we solved by imagining a straight line 
going from each robot to the player and measuring the angle between that line and one of the axes, whichever multiple-of-45-degrees 
angle that angle was closest to would determine its direction).