# 🎟️ Ticket Booking System (C Project)

A **C-based Ticket Booking System** that simulates ticket reservation, cancellation, and management using **Data Structures & Algorithms**.  
It supports **Queue, Stack, Linked List, Sorting, Searching, and Fractional Knapsack** for a complete ticketing workflow.

---

## 🚀 Features

### 👤 User Side
- Book up to **3 tickets per person**
- Real-time **seat availability check** (1–99)
- **Ticket cancellation** with refund
- **Search tickets** by passenger name
- **Ticket price handling** with balance check
- Action **history tracking**

### 🔑 Admin Panel
- **Password protected** (default: `0000`)
- Display all booked tickets
- Sort tickets:
  - By Seat Number (**Insertion Sort**)
  - By Passenger Name (**Selection Sort**)
  - By Ticket ID (**Merge Sort**)
  - By Cost/Ticket Ratio (**Quick Sort**)
- Allocate VIP goodies using **Fractional Knapsack Algorithm**
- View complete action **history log**

---

## 🛠️ Data Structures Used
- **Array** – To store tickets
- **Queue** – For ticket processing
- **Stack** – For cancellation and overflow handling
- **Linked List** – To maintain booking/cancellation history
- **Sorting Algorithms** – Insertion, Selection, Merge, Quick Sort
- **Fractional Knapsack** – Resource allocation (VIP goodies)

---

## 📸 Sample Menu

1. Book a Ticket
2. Display Tickets
3. Cancel Ticket
4. Search Ticket (Name)
5. Admin Panel
6. Exit
```

---

## 📊 Usage Examples

### ✅ Booking a Ticket
```
Enter passenger name: Mahdi
The price of each ticket is 200 taka only
How many tickets (1-3)? 2
Enter seat number for ticket 1 (1-99): 5
Ticket booked successfully.
Enter seat number for ticket 2 (1-99): 8
Ticket booked successfully.
Total cost: 400 Taka
Payment successful!! Returned amount: 0 Taka
```

### ❌ Cancelling a Ticket
```
Enter seat number to cancel: 5
Cancelling ticket: ID: 1, Name: Mahdi, Seat: 5
Returned amount: 200
Thanks for using our system!
```

### 🔍 Searching a Ticket
```
Enter passenger name to search: Mahdi
Ticket Found:
ID: 2, Name: Mahdi, Seat: 8
```

### 🔑 Admin Panel (Sorting Example)
```
~~~~ Admin Panel ~~~~

1. Display All Tickets
2. Sort Tickets by Seat Number
3. Sort Tickets by Passenger Name
4. Sort Tickets by Ticket ID
5. Sort Tickets by Cost/Number of Tickets
6. Discount Allocation (Fractional Knapsack)
7. View Total History
8. Exit Admin Panel

Enter your choice: 2
Tickets sorted by seat number.
List of Tickets:
ID   Name   Seat
2    Mahdi   8
```

---

## ⚙️ Installation & Run

### Requirements:
- GCC compiler (Linux/Windows)
- Enable ANSI escape sequences for colored output:
  ```
  reg add HKCU\Console /v VirtualTerminalLevel /t REG_DWORD /d 1
  ```

### Compile & Run:
```bash
gcc ticket_booking.c -o ticket_booking
./ticket_booking
```

---

## 🔒 Admin Panel
Default password:  
```
0000
```

---

## 📂 Project Structure
```
ticket_booking.c   # Main C program
```

---

## 🎯 Learning Outcomes
- Practical use of **Data Structures** in real-life applications
- Implementation of multiple **sorting algorithms**
- Application of **Fractional Knapsack** in resource allocation
- Hands-on with **queues, stacks, linked lists**

---

## 👨‍💻 Author
- **Mahdi Hasan**  
  [LinkedIn](https://www.linkedin.com/in/mdmahdihasangub/) | [GitHub](https://github.com/seemahdi)

---
```

---


