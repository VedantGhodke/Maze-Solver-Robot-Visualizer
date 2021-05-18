
<h1 align="center">Maze Solver Robot - Visualizer</h1>
<h2 align="center">A Tool For Visualizing Various Path Finding Algorithms</h2>
<h3 align="center">Vedant Ghodke</h3>

# Algorithms Used
<ul>
  <li>
    Dijkstra's Algorithm
  </li>
  <li>
    A* Algorithm
  </li>
   <li>
    Depth-First-Search (DFS) Algorithm
  </li>
  <li>
    Breadth-First-Search (BFS) Algorithm
  </li>
</ul>

### Live Demo : Maze Solver Robot - Visualizer ([Demo Link](https://vedantghodke.github.io/Maze-Solver-Robot-Visualizer/))

> The project is built using different shortest-path algorithms (Dijkstra, A*, DFS, BFS) and generates grid using a maze-generation algorithm (recursive backtracking) with VanillaJS and with a backend code of Python. The project also gives the user ability of controlling the grid structure and the distribution of the blocks along with the speed of the visualization (delay parameter) and the size of the grid.


# Working Methodology

1) Users can drag around the start and end node to set them in any spot.
2) Users can then choose a speed of the visualization (delay). (By default delay = 10ms between easch visualisation step). 
3) User can generate a maze by drawing on the grid or by using maze generation algorithms like recursive backtracking (Prims algorithm) and DFS. 
4) Users can optionally choose to clear the maze or draw walls by clicking and dragging the mouse.
5) Users can optionally randomize the walls in the maze and add more walls by dragging the mouse.

# Requirements
1) Python3
2) OpenCV
3) HeapQ
4) MatPlotlib
5) JavaScript

# Steps Of Implementation (Backend)
## 1) Input image live feed to the system using camera:

![IMAG2747](https://user-images.githubusercontent.com/24778913/54785699-e84b8680-4c4c-11e9-99d3-8a50f430c43f.jpg)
<br>
<br>
## 2) Detection of the industrial maze using image thresholding:

![Screenshot from 2019-03-22 02-23-11](https://user-images.githubusercontent.com/24778913/54785762-07e2af00-4c4d-11e9-8472-08152d4930b1.png)
<br>
<br>
## 3) Conversion of the input image into a smaller grid (for size optimization):

![Screenshot from 2019-03-22 02-28-13](https://user-images.githubusercontent.com/24778913/54787244-22b72280-4c51-11e9-83b4-04e8021a5ee3.png)
<br>
<br>
## 4) Input for the start and the end point(s) from the end user:

![Screenshot from 2019-03-22 02-28-53](https://user-images.githubusercontent.com/24778913/54785826-33659980-4c4d-11e9-9c9f-c7e87fa48fb7.png)
<br>
<br>
## 5) Solution of the micromouse grid using A-Star Algorithm:
The sources that were useful for the design of the algorithmic code have been provided in the 'References' section in document below.<br>
![Screenshot from 2019-03-22 02-29-04](https://user-images.githubusercontent.com/24778913/54785841-3f515b80-4c4d-11e9-87f1-57d7b7badad7.png)
<br>
<br>

# Upcoming Target Improvements:
1) The process of conversion of a high resolution image into a grid is not accurate and efficient. The process to improve the accuracy and efficiency with a different approach is in progress.<br>
2) Plotting of the result on the live camera feed is not currently implemented. The process to do the same is being worked upon.<br>

### Live Demo : Maze Solver Robot - Visualizer ([Demo Link](https://vedantghodke.github.io/Maze-Solver-Robot-Visualizer/))

# References:
1) <a href="https://www.youtube.com/watch?v=ySN5Wnu88nE&t=199s">YouTube - 'Computerphile'</a><br>
2) <a href="https://www.youtube.com/watch?v=aKYlikFAV4k">YouTube - 'Coding Train'</a><br>
3) <a href="https://medium.com/@nicholas.w.swift/easy-a-star-pathfinding-7e6689c7f7b2">Medium - A* Pathfinding</a><br>
4) <a href="https://www.raywenderlich.com/3016-introduction-to-a-pathfinding">Raywender Lich</a><br>
5) <a href="https://www.analytics-link.com/single-post/2018/09/14/Applying-the-A-Path-Finding-Algorithm-in-Python-Part-1-2D-square-grid">Analytics Link - A* Algorithm</a>

