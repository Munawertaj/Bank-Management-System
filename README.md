# 🏦 Bank Account Management System

A simple **Bank Management System** built with **Java (OOP Basics)**, **Spring Boot**, and **Thymeleaf**. This project demonstrates basic banking features such as user registration, login, deposit, withdrawal, transfer, and transaction history — all without using any database (in-memory data with `ArrayList` / `HashMap`).

---

## 📌 Features
- ✅ User Registration with auto-generated account number
- ✅ Secure Login with credential validation
- ✅ Dashboard with multiple operations:
  - View User Details
  - Deposit Money
  - Withdraw Money
  - Transfer Between Accounts
  - View All Transactions
- ✅ Thymeleaf for front-end rendering
- ✅ Styled with Bootstrap
- ✅ Data stored in-memory using Java Collections

---

## 🛠 Technologies Used
- Java (OOP Concepts)
- Spring Boot (for routing and application flow)
- Thymeleaf (HTML rendering)
- Bootstrap (UI styling)
- No database used (data is stored in `ArrayList` / `HashMap`)

---

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/bank-management-system.git
   cd bank-management-system
   ```

2. **Open in IDE** (like IntelliJ IDEA, Eclipse, VS Code)

3. **Build and Run the application**
   - Run the `BankManagementSystemApplication.java` file.

4. **Access in browser**
   ```
   http://localhost:8080/
   ```

---

## 📂 Project Structure
```
src/
 └── main/
     ├── java/
     │   └── com.BankApp.BankManagementSystem/
     │       ├── controller/
     │       ├── model/
     │       ├── service/
     │       └── BankManagementSystemApplication.java
     └── resources/
         ├── templates/       <-- Thymeleaf HTML files
         └── application.properties
```

---

## ✨ Screens Included
- Home Page
- Register Page
- Login Page
- Dashboard
- User Details
- Deposit, Withdraw, Transfer
- Transaction History

---

## 🙌 Acknowledgements
Built as a learning project to demonstrate:
- Java Basics & OOP Principles
- Spring MVC Controller-Service Design
- Thymeleaf Templating Engine
- Web App Development without a Database