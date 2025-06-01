# 📚 Bookstore Management System in C++

This is a console-based Bookstore Management System developed in C++ using Object-Oriented Programming (OOP) concepts. The system allows both **Admin** and **User (Customer)** access to manage or purchase books. It utilizes file handling for data persistence and runs entirely on the terminal/command-line interface.

---

## 🛠️ Features

### 🔐 Login System
- **Admin** login with username and password
- **User** can directly access limited features

### 👤 Admin Functionalities
- Add new books
- Display all available books
- Update existing book records
- Delete books

### 👥 Customer Functionalities
- View list of available books
- Purchase books with receipt generation (includes GST)
  
---

## 🧰 Tools & Technologies
- C++
- OOPs concepts (Classes, Inheritance, File Handling)
- File I/O (`fstream`)
- Basic console input/output

---

## 💾 File Storage
Books data is stored and updated in local `.txt` files:
- `D:// book.txt` — Main book data file
- `D:// book1.txt` — Temporary file used during update/delete operations

> **Note:** Ensure the `D://` directory exists on your system or change the file paths to match your environment.

---

## 🔄 Purchase Workflow
1. User selects a book by ID.
2. System checks stock and price.
3. On confirmation, generates a receipt with:
   - Book details
   - Quantity, cost, GST (12%)
   - Mode of payment

---

## 🧪 Sample Admin Credentials
- **Username:** `ABC`
- **Password:** `1234`

---

## 🔄 Future Improvements
- Replace text files with a proper database (e.g., SQLite, MySQL)
- Implement better input validation
- Use dynamic memory and pointers for more advanced C++ features
- Add GUI interface using frameworks like Qt or WinForms

---

## 🏁 Getting Started

### ✅ Prerequisites
- C++ Compiler (e.g., g++, Visual C++)
- Terminal or IDE (e.g., Code::Blocks, Visual Studio, Dev-C++)

### ▶️ Running the Program
1. Clone this repository or download the `.cpp` file.
2. Compile using a C++ compiler:

```bash
g++ -o bookstore main.cpp
./bookstore
