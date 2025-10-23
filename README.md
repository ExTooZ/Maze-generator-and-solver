# Maze Generation Project
## Description
This project is created by 3 TU Berlin student (Sebastianus Dustin Susanto, Gregorius Kevin Soetanto, Georgius Kenneth Liauwangsa) at the end of the module named "Computer Orinetierte Mathematik". The aim of this project is to create a maze generator that has its starting point and end point randomly generated within the maze and solve it immediately after the generation of the maze. The programming language that is used here is Julia ver 1.10.2.


## How to Run

1. Open a Julia REPL.
2. Navigate to your project folder:
3. Use the following command to include the file:
```julia
 include("MazeGeneration.jl")
````
4. Run the program with the following line:
````julia
MazeGeneration.maze(5,5)
````
The size of the maze can be any size. Do keep in mind that larger mazes will cause it to load longer. It is recmmonded to have a limit of 20x20 maze.








