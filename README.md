# Navmesh Pathfinding

A video demo of a navmesh-based pathfinding system, implemented on top of Prime Engine for Csci522 - Game Engine Development, at the University of Southern California.

## Project description

The goal of this project was to implement a navmesh-based pathfinding system on a custom game engine using the A* algorithm. The source code for the Engine is under copyright and thus unable to be distributed, so I have enclosed videos of the project to show how it progressed.

The first video, "1_Navmesh_StupidPath", demonstrates a fully working navmesh divided into cells, and a functional A* algorithm to drive the agent between cells in the shortest path to reach the camera, but with the caveat of an unsmoothened path. It is worth noting that the cells have been magnified to demonstrate the "Stupid" path; although the A* algorithm is correct and the agent does find the shortest path between itself and the camera, the path it follows is jagged and unnatural.

The second video, "1_Navmesh_PathSmoothening", demonstrates the same system working with an implementation of the "Simple Stupid Funnel Algorithm" to ensure a more natural path for the soldier. As the video demonstrates, the agent walks in a path that appears perfectly natural, and is also able to detect when the camera is over a gap/unreachable cell, thereby stopping its pursual of the camera.

## Built With

* [PrimeEngine](https://sites.google.com/site/artemscode/home) - Many thanks to Artem Kovalovs, instructor of Csci522 for allowing us to build on top of his engine
