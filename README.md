# Final-Project-Group5

This is a program to drive a robot through a maze using Depth First Search as it's path-planning algorithm. The program is interfaced with Micromouse simulator for visualizing the maze and the robot in real-time.The concepts of object-oriented programming, inheritance, and dynamic polymorphism were used to develop this project.


Overview
=====================================================================================

Steps to run this program:-

1. Visit this Github link https://github.com/mackorone/mms#building-from-source  to install Micromouse simulator.

2. Build the simulator using the following command: /user# cd mms/src
                                                    /user# qmake && make

3. Run the simulator using following command: ../bin/mms

4. Parameters to be changed in the simulator:-

   Name:- Input your desired name.

   Directory:- ../../FinalProjectGroup5/Final-Project-Group5/src

   Build Command:- g++ API/api.cpp LandBasedTracked/landbasedtracked.cpp LandBasedWheeled/landbasedwheeled.cpp Maze/maze.cpp Algorithm/algorithm.cpp ../main.cpp

   Run Command:- ./a.out

5. Run the Simulator.

Output of the program is :-

![Output of the program](/Final-Project-Group5/FinalProject_Output.gif)
























