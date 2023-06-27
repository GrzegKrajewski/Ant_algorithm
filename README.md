### Traveling merchant problem solved with an algorithm
## Ant algorithm implementation in python
This code aims to solve the traveling merchant problem using the ant algorithm, we take N random points from 2 dimensional X, Y space where X and Y take values from 0 to 100. Then using the ant algorithm we create the shortest path connecting all the points where every point can be visited only once.

The algorithm works in such a way that ants start from different points and try to determine the best path, it chooses the next point to travel to based on the distance to it and pheromones left by other ants at this path in different iterations. This way we create the most 'popular' paths ousing pheromones, they tend to be more efficient. Alpha and Beta parameters influence how Based ants are when choosing next point which they should visit, beta accounts for influence of distance between points and alpha changes influence of pheromones left at path. 
Ideally, we pick a number of ants equal to the count of points in the given example, then each and can have its own unique start point to unique localize the function.
