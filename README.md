# 💳 ATM Simulation System (Java)

A simple **ATM simulation program** written in Java that demonstrates core Object-Oriented Programming (OOP) principles such as encapsulation, abstraction, and interfaces.  
The program allows users to **check balance, deposit, withdraw, view mini statements**, and **exit** the ATM interface via console.

---

## 🧩 Features

- 🔐 User authentication (PIN-based)
- 💰 Check account balance
- ➕ Deposit amount
- ➖ Withdraw amount
- 📄 View mini-statement (transaction history)
- 🚪 Exit system safely

---

## 🗂️ Project Structure

ATM-Simulation/
│
├── Atm.java # Represents ATM entity (account details, operations)
├── AtmMain.java # Entry point with main() method (menu-driven interface)
├── AtmOperationImpl.java # Implementation class containing ATM logic
└── AtmOperationInterf.java # Interface defining ATM operations

yaml
Copy code

---

## ⚙️ How It Works

1. The user is prompted to **enter an ATM number and PIN**.
2. If credentials match the predefined user details, access is granted.
3. The program displays a **menu** with the following options:
   - Check Balance  
   - Deposit Amount  
   - Withdraw Amount  
   - View Mini Statement  
   - Exit  
4. The user can perform multiple transactions until choosing to exit.

---

## 🚀 How to Run

### Prerequisites
- **Java JDK 8 or above**
- **Any IDE** (e.g., IntelliJ IDEA, Eclipse, VS Code) or terminal access

### Steps
1. Clone or download this repository:
 
Compile the Java files:
javac *.java
Run the program:

bash
Copy code
java AtmMain
🧠 Concepts Used
Interfaces for defining contracts

Class and Object for real-world simulation

Encapsulation for secure data handling

Abstraction for hiding internal logic

Collections (Map) for transaction storage

Control Structures for menu navigation

🧾 Example Output
mathematica
Copy code
Enter ATM number: 12345
Enter PIN: 1234

1. View Available Balance
2. Withdraw Amount
3. Deposit Amount
4. View Mini Statement
5. Exit

Enter Choice: 2
Enter amount to withdraw: 500
Collect your cash and remove card.
