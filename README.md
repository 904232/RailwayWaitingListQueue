Railway Waiting List Queue System (Java)

Introduction

The Railway Waiting List Queue System is a Java console application developed to demonstrate the practical use of the Queue (FIFO) data structure. The project simulates basic railway waiting list operations and serves as a foundational example for beginners learning data structures, Java Collections, and menu-driven program design.

Features

Add a passenger to the waiting list

Confirm the ticket for the next passenger in the queue

Display the current waiting list

Handle empty queue conditions

Uses LinkedList as the Queue implementation

Technologies Used

Java (JDK 8 or higher)
Java Collections Framework
LinkedList (Queue implementation)
Scanner for console input

Project Structure

RailwayWaitingList/
└── RailwayWaitingList.java

How to Run

Using VS Code
Install the Java Extension Pack.
Open the project folder.
Open RailwayWaitingList.java.
Click the Run button.

Interact through the integrated terminal.

Using Terminal
javac RailwayWaitingList.java
java RailwayWaitingList

Sample Output
===== Railway Waiting List System =====
1. Add Passenger to Waiting List
2. Confirm Ticket for Next Passenger
3. View Waiting List
4. Exit
Enter your choice:


Example interaction:

1
Enter passenger name: Anita
Anita added to waiting list.

1
Enter passenger name: Ravi
Ravi added to waiting list.

3
Current Waiting List: [Anita, Ravi]

2
Ticket confirmed for: Anita

Concepts Demonstrated

Queue (FIFO) operations
Java Collections API
Input handling and validation
Menu-driven console application design
basic procedural logic and data structure usage

Future Enhancements

Implement seat capacity logic
Auto-confirmation when seats become available
Store and load data from a file
GUI version using JavaFX
Passenger cancellation functionality
