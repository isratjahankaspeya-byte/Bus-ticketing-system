# 🚌 Bus Ticketing System

A terminal-based Bus Ticketing System developed in **C Programming Language** using **Structures**, **Functions**, and **File Handling**.

This project allows users to book, search, view, and cancel bus tickets while storing data permanently using text files.

---

## 📌 Project Overview

The Bus Ticketing System is a simple management application designed to automate the process of bus ticket booking and management.

Instead of maintaining tickets manually, the system provides a structured and efficient way to:

- View available buses
- Book tickets
- Search tickets
- View all booked tickets
- Cancel tickets

Ticket information is stored using file handling, ensuring data persistence between program executions.

---

## 🎯 Objectives

- Learn and apply C programming concepts
- Practice structures and user-defined data types
- Implement file handling operations
- Use functions for modular programming
- Build a real-world management system

---

## ✨ Features

### 1. Show Available Buses
Displays all available buses.

Example:
```
1. Dhaka Express
2. Green Line
3. Hanif Enterprise
```

### 2. Book Ticket
Allows passengers to enter:

- Name
- Age
- Bus Name
- Seat Number

A unique Ticket ID is generated automatically.

### 3. View All Tickets
Displays all booked tickets stored in the file.

### 4. Search Ticket
Searches a ticket using Ticket ID.

### 5. Cancel Ticket
Deletes a ticket record using Ticket ID.

### 6. Persistent Storage
Data remains saved even after the application is closed.

---

## 🏗️ Project Structure

```
Bus-Ticketing-System/
│
├── bus_ticket.c
├── tickets.txt
├── counter.txt
├── README.md
└── Project_Report.pdf
```

---

## 📊 Data Structure Used

```c
struct Ticket {
    int ticketID;
    char passengerName[50];
    int age;
    char busName[50];
    int seatNumber;
};
```

---

## 🔧 Functions Used

| Function | Description |
|-----------|-------------|
| showBuses() | Display available buses |
| bookTicket() | Book and save ticket |
| viewTickets() | Display all tickets |
| searchTicket() | Search ticket by ID |
| cancelTicket() | Cancel ticket |
| main() | Main menu controller |

---

## 💾 File Handling

The project uses text files for persistent storage.

### tickets.txt
Stores all ticket records.

Example:

```
1000|Abu|22|Green Line|12
1001|Rahim|25|Hanif Enterprise|07
```

### counter.txt

Stores the last generated Ticket ID.

Example:

```
1002
```

---

## ▶️ How to Compile and Run

### GCC (Linux/Mac)

```bash
gcc bus_ticket.c -o bus_ticket
./bus_ticket
```

### GCC (Windows)

```bash
gcc bus_ticket.c -o bus_ticket.exe
bus_ticket.exe
```

### Code::Blocks

1. Open Code::Blocks
2. Create an Empty Project
3. Add the source code file
4. Press **F9** to Build and Run

---

## 📸 Sample Menu

```text
========================================
        BUS TICKETING SYSTEM
========================================
1. Show Available Buses
2. Book Ticket
3. View All Tickets
4. Search Ticket
5. Cancel Ticket
0. Exit
========================================
```

---

## 🧪 Testing Results

| Test Case | Result |
|------------|---------|
| Book Ticket | ✅ Pass |
| View Tickets | ✅ Pass |
| Search Ticket | ✅ Pass |
| Cancel Ticket | ✅ Pass |

All core functionalities were tested successfully.

---

## 🚀 Future Improvements

- Admin Login System
- Fare Calculation
- Seat Availability Validation
- Interactive Seat Map
- Bus Schedule Management
- Database Integration (SQLite/MySQL)
- Graphical User Interface (GUI)
- Online Booking Support

---

## 📚 Concepts Used

- Structures
- Functions
- Loops
- Conditional Statements
- Switch Case
- File Handling
- String Manipulation

---

Academic Project – C Programming

---

## 📄 License

This project is created for educational and academic purposes.

Feel free to use, modify, and improve it for learning.
