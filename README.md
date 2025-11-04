# 🏥 Hospital Management System (Java)

A simple **Java-based console application** that manages hospital data — including doctors and patients — using **Object-Oriented Programming (OOP)** principles.  

This project demonstrates how real-world entities like doctors and patients can be modeled in Java classes and managed through a simple text-based interface.

---

## 🚀 Features

- Add new patients and doctors  
- View existing records  
- Delete patients or doctors  
- Simple menu-driven system  
- Fully written in **Core Java** (no external libraries)

---

## 🧠 Algorithm & Logic (Explained Simply)

1. **Main Control (HospitalManagementSystem.java)**  
   - Acts as the *central brain* of the application.  
   - Uses a **menu loop** (`while` or `do-while`) to show options like Add / View / Delete.  
   - Based on user input, it performs the desired action by calling methods from `Doctor` or `Patient` classes.  
   - Stores all doctors and patients inside **ArrayLists** (like dynamic lists in Java).  

   👉 Think of it like a manager who maintains two lists: one for doctors and one for patients.  

---

2. **Doctor.java**  
   - Represents each doctor as an **object** with fields like:
     ```java
     String name;
     int id;
     String specialization;
     ```
   - Includes **getters and setters** (Encapsulation).  
   - Helps the main system to **add**, **view**, or **delete** doctors easily.  

   👉 In interviews, you can say:  
   *“Doctor class is a blueprint for doctor objects. It demonstrates encapsulation and data abstraction.”*

---

3. **Patient.java**  
   - Works the same way as `Doctor.java` but for patients.  
   - Fields may include:
     ```java
     String name;
     int age;
     String disease;
     ```
   - Used to create, store, and display patient data.  

   👉 You can explain:  
   *“Patient class models the patient details and provides methods to access and modify them.”*

---

## 🔄 Workflow Summary

1. Program starts → shows main menu.  
2. User chooses an action (e.g., Add Patient).  
3. System takes input → creates a new object (`Patient` or `Doctor`).  
4. Object gets stored in an ArrayList.  
5. The user can later view or remove records from that list.  

It’s basically a **CRUD** (Create, Read, Update, Delete) style console app.

---

## 🧩 Concepts Used

- ✅ **Classes & Objects** — Represent doctors and patients.  
- ✅ **Encapsulation** — Private fields with public getters/setters.  
- ✅ **Collections (ArrayList)** — To store multiple records dynamically.  
- ✅ **Control flow & loops** — For menu-driven interaction.  
- ✅ **Simple I/O (Scanner)** — To read input from users.

---

## 💡 Possible Future Improvements

- Connect to a **database (MySQL)** to store real hospital data.  
- Add **appointments** or **billing features**.  
- Build a **GUI version** using JavaFX or Swing.  
- Add **file storage** (save & load data between runs).

---

## 🧑‍💻 Author

**Hari** — just a chill guy 😎  
> Passionate about coding, data, and building cool stuff in Java and Python.

---

## 🧾 License

This project is open-source and free to use for learning and development.

---

