# Metro Map Implementation using Dijkstra's Algorithm
#This C++ project is an implementation of a metro map system using Dijkstra's algorithm. The program calculates the minimum number of stations between a source station and every other station on the map.
#


Metro Map Implementation using Dijkstra's Algorithm
This C++ project is an implementation of a metro map system using Dijkstra's algorithm. The program calculates the minimum number of stations between a source station and every other station on the map.

Getting Started
To compile and run the program, follow these steps:

Clone this repository to your local machine.
Navigate to the directory containing the source code.
Compile the source code using a C++ compiler. For example:
Copy code
g++ metro_map.cpp -o metro_map
Run the executable:
bash
Copy code
./metro_map
How it Works
The program represents the metro map as a weighted graph, where each station is a node and the distance between stations represents the weight of the edge connecting them. Dijkstra's algorithm is then applied to find the shortest path from a given source station to all other stations on the map.

Usage
Upon running the program, you will be prompted to enter the source station index. The program will then display the minimum number of stations between the selected source station and every other station on the map.

Note
The map is hardcoded within the source code for simplicity. You can modify the graph array to represent a different metro map if needed.
This implementation assumes that the metro map is an undirected graph.
Dependencies
This project requires a C++ compiler to build and run.
#Output

![Screenshot 2024-03-24 214534](https://github.com/pkakkar521/Dsa-Projects/assets/114657672/f7cbfb0e-72ac-41fd-ae46-a6c8e13666f3)


![Screenshot 2024-03-24 214605](https://github.com/pkakkar521/Dsa-Projects/assets/114657672/0ab94288-1ff7-44fe-bda7-1aeaea4fca17)


 #Student Database Management System 

 Implemented using a B-tree data structure for efficient storage and retrieval of student records. Here's a description of the key components and functionalities of the code:

Authentication Class:
Handles user authentication before accessing the database.
Allows multiple login attempts with a maximum of 5 tries.
Student Structure:
Represents the structure of a student record containing fields such as roll number, first name, last name, course, and hostel name.
BTreeNode Class:
Represents a node in the B-tree data structure.
Manages operations like insertion, deletion, splitting, merging, and traversal of nodes.
Each node can hold multiple student records and child pointers.
BTree Class:
Manages the B-tree structure.
Provides methods for searching, inserting, and deleting student records.
Utilizes the BTreeNode class to perform operations on the tree nodes.
Main Function:
Implements the user interface for interacting with the database system.
Allows users to perform various operations such as searching, adding, listing, modifying, and deleting student records.
The main loop continues to prompt the user for actions until the program is exited.
Description of Main Functionality:
Authentication: Before accessing the database functionalities, users are required to authenticate themselves with a username and password. Authentication is limited to 5 login attempts.
Menu Options:
Search Record: Allows users to search for a student record by roll number.
Add Records: Enables users to add new student records to the database.
List Records: Displays all student records stored in the database.
Modify Records: Allows users to modify existing student records based on the roll number.
Delete Records: Enables users to delete student records based on the roll number.
Exit Program: Terminates the program execution.
Additional Notes:
The program interacts with users through the console using text-based menus and prompts.
Student records are stored persistently in a CSV file named "students.csv" using append mode, ensuring data retention across program executions.
Error handling is included for invalid input and unsuccessful operations.
The B-tree data structure is utilized to maintain efficiency in storing and managing large datasets of student records.
Overall, this program provides a robust and user-friendly interface for managing student records efficiently using a B-tree-based database system.

#Output

