# Dijkstra-algo

#Overview

#This project implements Dijkstra's Algorithm in C++ to find the shortest path between two nodes in a weighted graph. The program allows users to either manually enter the graph structure or use a predefined dataset.

#Features

#Uses Dijkstra’s Algorithm to compute the shortest path from a starting node to an ending node.

#Supports hardcoded graph data for easy testing.

#Handles user input for specifying start and end nodes.

#Displays the shortest path cost and the corresponding path taken.

#Efficient implementation using unordered maps and priority queues (set-based approach).

#Input Format

#The number of edges is predefined in the hardcoded graph.

#The user enters two values:

#Start node

#End node

#Example Usage

#Enter start node: 1
#Enter end node: 4

#Expected Output:

#Shortest path cost: 8
#Path: 1 -> 3 -> 5 -> 4

#How It Works

#The graph is represented using an adjacency list.

#The Dijkstra function initializes distances and parents for path tracking.

#A priority queue (set) is used to process the nodes efficiently.

#After processing, the shortest path and cost are displayed.

#Hardcoded Graph Structure

#The graph used in the hardcoded dataset is:

1 --(4)-- 2
    |        |
   (2)      (10)
    |        |
    3 --(5)-- 2
    |        |
   (3)      (1)
    |        |
    5 --(1)-- 4
