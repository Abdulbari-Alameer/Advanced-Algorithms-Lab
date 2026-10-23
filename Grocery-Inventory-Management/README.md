# 🛒 Grocery Inventory Management System (C++)

## 📌 Project Overview
This project is a **Grocery Store Inventory Management System** implemented in **C++**.  
It manages grocery items using **custom data-structure classes** built on `std::vector`:

- A dynamic item list
- Queues
- Stacks

The system supports **persistent storage using Binary Files**, allowing the inventory data to be saved and reloaded.

---

## 🎯 Key Features

- ✅ Add, Update, Delete inventory items  
- ✅ Track expiry dates of products  
- ✅ Category-wise Queue processing  
- ✅ Stock management using Stack (LIFO)  
- ✅ Binary file storage (No Database used)  

---

## 🧠 Core Data Structures Used

| Structure | Purpose |
|------------|----------|
| Dynamic list (`std::vector`) | Store inventory records |
| Queue | Handle expiry tracking per category |
| Stack | Manage stock movement (LIFO logic) |
| Binary Files | Persistent data storage |

---

## ⚙️ Build & Run Instructions

### 🔹 Requirements
- G++ Compiler  
- Linux / Windows (CLI support)

### 🔹 Compile
```bash
g++ Grocery_Store_Management_System.cpp -o grocery_sys
./grocery_sys
