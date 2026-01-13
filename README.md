# Product Management System

## 📦 Project Overview

The **Product Management System** is a desktop-based application designed to manage product records efficiently. It allows users to **add, update, delete, search, and persist product data** using a clean graphical interface.
This project is built for **academic, learning, and demonstration purposes**, focusing on structured programming, data persistence, and UI-based CRUD operations.

---

## 🎯 Objectives

* Implement a structured **CRUD-based management system**
* Demonstrate **object-oriented design principles**
* Practice **file-based data persistence**
* Provide a simple and user-friendly **WPF GUI**
* Support academic submissions and demos

---

## 🛠️ Tech Stack

| Component    | Technology                      |
| ------------ | ------------------------------- |
| Language     | C#                              |
| Framework    | .NET (WPF)                      |
| UI           | Windows Presentation Foundation |
| Data Storage | JSON File                       |
| IDE          | Visual Studio                   |
| Platform     | Windows                         |

---

## ✨ Features

* ➕ Add new products
* ✏️ Update existing products
* ❌ Delete products
* 🔍 Search products by name or category
* 📄 Persistent storage using JSON
* 📊 Automatic total value calculation
* 🧩 Clean and modular architecture
* 🖥️ Responsive WPF-based UI

---

## 🧱 Project Structure

```
ProductManagement/
│
├── Models/
│   └── Product.cs
│
├── Data/
│   ├── IProductRepository.cs
│   └── JsonProductRepository.cs
│
├── UI/
│   └── ProductWindow.xaml
│   └── ProductWindow.xaml.cs
│
├── Assets/
│   └── ProductManagement_ClassDiagram.png
│
├── products.json
├── README.md
└── ProductManagement.sln
```

---

## 📐 System Design

The project follows a **layered architecture**:

* **Model Layer** → Represents product entities
* **Data Layer** → Handles file persistence (Repository Pattern)
* **UI Layer** → Manages user interaction (WPF)



---

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ProductManagement.git
   ```
2. Open the solution in **Visual Studio**
3. Build the solution
4. Run the application (`Start` button)

---

## 📚 Learning Outcomes

* Understanding of **OOP concepts**
* Hands-on practice with **WPF applications**
* Experience with **Repository Pattern**
* File-based **JSON serialization**
* GUI event handling in C#

---

## 🚀 Future Improvements

* Add database support (SQLite / SQL Server)
* Implement user authentication
* Add product export (CSV / PDF)
* Improve UI styling
* Add unit testing

---

## 🤝 Contribution

This project is intended for **educational use**.
Feel free to fork the repository and improve functionality, UI, or documentation.

---

## 📄 License

This project is released for **academic and educational purposes only**.


