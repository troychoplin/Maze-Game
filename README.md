# Table of Contents
1. [Introduction](#in)
2. [System Requirements](#sr)
3. [Installation](#install)  
4. [How To Play](#htp)
5. [Custom Maze Levels](#cml)
6. [Troubleshooting](#ts)
7. [Support Information](#supp)
8. [Contributions](#cs)
9. [License](#li)
<br>
<br> 


# MAZE GAME <a name="in"></a> 

Welcome to MazeGame! This game is a simple command-line program allowing users to navigate through a maze. 

This file contains useful instructions on how to configure, run, and play MazeGame. 
<br>
## System Requirements (Description of Materials) <a name="sr"></a> 
* PC with updated Java installation

   * If Java is not installed, download and install from <a href="https://www.java.com/en/download">here.</a>
   
* Windows operating system
    
    * Required to execute the .bat game files
<br>

## Installation <a name="install"></a> 
* Download the game in ZIP format from <a href="https://github.com/troychoplin/Maze-Game/archive/master.zip">here.</a>

* Unzip the downloaded folder and extract to a specified location on your computer.

* To start the game, run either "MazeGame(easy).bat" or "MazeGame(hard).bat" depending on the desired level of difficulty.
<br>

## How To Play <a name="htp"></a> 

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


<img src="https://github.com/troychoplin/Maze-Game/blob/master/easymap.PNG?raw=true" alt="Maze Game Map">

### Step 2
You will be prompted to enter a desired move. In order to make a move type one of the following and press ENTER:
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
To play again, re-run the MazeGame bat file and try to minimie the number of moves made!

## Custom Maze Levels (Optional) <a name="cml"></a> 
- Maze levels are text files containing a 39x19 grid of 1's and 0's. 
   * 1's represent blocked spaces
   * 2's represent open spaces
- Create custom maze levels by creating a text file containing 19 rows and 39 columns of 1's and 0's.
   * Include a "S" somewhere on the grid to mark the starting position.
   * Include a "G" somewhere on the grid to mark the goal position. 
   * These special markers will take the place of an open or blocked space.
- When creating custom levels, be sure to consider the path the player must take to reach the goal. 
   * The game should be winnable!
   
- See below for an example of the text file used to create the easy map.
   <img src="https://github.com/troychoplin/Maze-Game/blob/master/Maze%20Game%20Level%20File.png?raw=true" alt="Maze Game Text File">
   
- To install and use the custom level: 
   * First, save the newly-created text file to the data folder found in the Maze Game folder.
   * Create another new text file, and type the following in the file: 
        
   <img src="https://github.com/troychoplin/Maze-Game/blob/master/Custom%20level%20bat%20file.png?raw=true" alt="Maze Game Custom BatFile">
   
   * NOTE: Replace FILENAME with the name of the created text file.
   
   * Save the file with the extension .bat instead of .txt to ensure that the program is runnable.
   * Ensure that the .bat file is located in the Maze Game folder.
   * Finally, simply run the .bat file to play the game with the new level!
<br>
   
## Troubleshooting <a name="ts"></a> 
* If the bat file does not open correctly, ensure that Java is installed and up-to-date.

* The bat file will only work with Windows PCs. If running Linux or Mac operating systems, the files must be compiled and executed manually. 

* If the game fails to load a custom level, ensure that the text file contains exactly 19 rows and 39 columns, and that it    includes a "S" and a "G" for the start and goal position, respectively.

* Each game is winnable so if you have trouble reaching the goal, keep trying!
<br>

## Support Information <a name="supp"></a> 
For any issues not covered here, contact me at:
choplint@appstate.edu 
<br>

## Contributions <a name="cs"></a> 
* The source code to MazeGame can be found <a href="https://github.com/troychoplin/Maze-Game">here.</a>

* Feel free to fork and make a pull request to offer contributions.
<br>

## License <a name="li"></a>
[MIT License](https://choosealicense.com/licenses/mit/)


