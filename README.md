# maze_runner
Description - 
This Python script uses the curses library to create a text-based interface for solving a maze. The maze is represented as a 2D list of strings, where # denotes walls, denotes open paths, O denotes the starting point, and X denotes the endpoint. The script finds the path from the start to the end using BFS and visually displays the pathfinding process.

Importing Modules: 
curses: Used for creating text-based user interfaces.
wrapper from curses: Simplifies the initialization and cleanup of the curses application.
queue: Used to implement the BFS algorithm.
time: Used for adding delays to visualize the pathfinding process.
