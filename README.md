# 🚆 Railway Waiting List Queue System (Java)

A simple Java console application that simulates a **railway waiting list** using the **Queue (FIFO)** data structure.  
This project helps beginners understand queue operations, menu-driven Java programs, and the Java Collections Framework.

---

## 📌 Features

- ➕ Add passengers to the waiting list  
- ✔ Confirm ticket for the next passenger (poll)  
- 👀 View the current waiting list  
- ❌ Alerts when waiting list is empty  
- 🧑‍💻 Uses `LinkedList` as a Queue  
- 🎯 Beginner-friendly project  

---

## 🗂 Project Structure

```
RailwayWaitingList/
 └─ RailwayWaitingList.java
```

---

## ▶️ How to Run the Project

### **Using VS Code**
1. Install **Java Extension Pack**  
2. Open the project folder  
3. Open `RailwayWaitingList.java`  
4. Click the **Run ▶ button**  
5. Enter options in the Run console  

---

### **Using Terminal**
```bash
javac RailwayWaitingList.java
java RailwayWaitingList
```

---

## 🖥 Example Output

```
===== Railway Waiting List System =====
1. Add Passenger to Waiting List
2. Confirm Ticket for Next Passenger
3. View Waiting List
4. Exit
Enter your choice:
```

Example:
```
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
```

---

## 💡 Concepts Used

- Queue (FIFO)
- Java Collections – LinkedList
- Scanner input handling
- Menu-driven program design

---

## 🌟 Future Improvements

- Add seat capacity logic  
- Auto-confirm when seats open  
- Save data to file  
- GUI version with JavaFX  
- Add cancellation feature  

---

## 👩‍💻 Author

**Karthiga S**  
Java Beginner | ECE Student  
Learning software development through hands-on projects.
