# MAZE GAME

Welcome to MazeGame! This game is a simple command-line program allowing users to navigate through a maze. 

This file contains useful instructions on how to configure, run, and play MazeGame. 

## System Requirements (Description of Materials)
* PC with updated Java Installation

   * If Java is not installed, download and install from <a href="https://www.java.com/en/download">here.</a>

## Installation
* Download the game in ZIP format from <a href="https://github.com/troychoplin/Maze-Game/archive/master.zip">here.</a>

* Unzip the downloaded folder and extract to a specified location on your computer.

* Run either "MazeGame(easy).bat" or "MazeGame(hard).bat" depending on the desired level of difficulty.


## How To Play

### Objective
The objective of the game is to reach the goal.

You begin the game at the start position indicated by a "S". 

The goal is represented at the "G" position on the map. 

Your current location on the map is indicated by "@". 

Navigate through the maze by avoiding blocked spaces represented by an "X".

As you move across the map, locations that have been previously visited will be marked with "." 

The game is over when you reach the goal. 

### Step 1
Run the .bat file to start the game. A command prompt containing the maze will open. 


![Maze Game Map](https://github.com/troychoplin/Maze-Game/blob/master/easymap.PNG).

### Step 2
You will be prompted to enter a desired move. In order to make a move type one of the following:
 1. "up" or "u" to move one space up.
 ```java
Please enter a move: u     //moves one space up
```
 2. "down' or "d" to move one space down.
 ```java
Please enter a move: d    //moves one space down
```
 3. "left" or "l" to move one space left.
 ```java
Please enter a move: l     //moves one space left
```
 4. "right" or "r" to move one space right.
  ```java
Please enter a move: r     //moves one space right
```

### Step 3
If you attempt to move outside of the game board or onto a blocked ("X") space, no action will be made and you will prompted to re-enter another move. 

### Step 4
After reaching the goal, the game will end and the total number of moves made will be displayed. 

### Step 5 
To play again, re-run the MazeGame bat file.

## Custom Maze Levels (Optional)
- Maze levels are text files containing a 39x19 grid of 1's and 0's. 
   * 1's represent blocked spaces
   * 2's represent open spaces
- Create custom maze levels by creating a text file containing 19 rows and 39 columns of 1's and 0's.
   * Include a "S" somewhere on the grid to mark the starting position.
   * Include a "G" somewhere on the grid to mark the goal position. 
- When creating custom levels, be sure to consider the path the player must take to reach the goal. 
   * The game should be winnable!
   
- See below for an example of the text file used to create the easy map.
![Maze Game Level File](https://github.com/troychoplin/Maze-Game/blob/master/Maze%20Game%20Level%20File.png).
   

## Troubleshooting
* If the bat file does not open correctly, ensure that Java is installed and up-to-date.

* The bat file will only work with Windows PCs. If running Linux or Mac operating systems, the files must be compiled and executed manually. 

* Each game is winnable so if you have trouble reaching the goal, keep trying!


## Contributions
* The source code to MazeGame can be found <a href="https://github.com/troychoplin/Maze-Game">here.</a>

* Feel free to fork and make a pull request to offer contributions.



## License
</a>[MIT License](https://choosealicense.com/licenses/mit/)


