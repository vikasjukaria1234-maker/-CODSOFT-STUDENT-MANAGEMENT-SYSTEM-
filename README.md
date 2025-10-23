# -CODSOFT-STUDENT-MANAGEMENT-SYSTEM-

# 🎓 Student Management System (Java GUI)

A **Java Swing-based Student Management System** that allows users to manage student data using a graphical interface.  
It supports adding, removing, searching, displaying, and saving student details to a file for persistence.

<img width="611" height="622" alt="Screenshot 2025-10-23 131500" src="https://github.com/user-attachments/assets/954791ae-8615-4e0b-a506-5e1186a8d1bf" />
---


## 🚀 Features
- ➕ **Add** new student details (name, roll number, grade, email)
- 🗑️ **Remove** a student by roll number
- 🔍 **Search** student by roll number
- 📋 **Display all** students
- 💾 **Save & Load** student data from a file (`students.dat`)
- ✅ **Input validation** (no empty fields)
- 💬 **User-friendly messages** and error handling

- 

---

## 🧩 Technologies Used
- **Java (JDK 8 or higher)**
- **Swing GUI**
- **File Handling** (`ObjectOutputStream` / `ObjectInputStream`)
- **Object-Oriented Programming**

---

## 🏗️ Project Structure
Student.java --> Represents individual student details
StudentManagementSystem.java --> GUI + Logic + File handling
students.dat --> Data file (auto-created on save)

yaml
Copy code

---

## 🧠 OOP Concepts Used
- **Encapsulation** → Data hidden inside `Student` class  
- **Composition** → `StudentManagementSystem` contains a list of `Student` objects  
- **Serialization** → Save and load student objects to/from a file  

---

## 🧾 Example Workflow
1️⃣ Add a Student  
→ Enter details → Click **Add**

2️⃣ Search a Student  
→ Enter roll number → Click **Search**

3️⃣ Remove a Student  
→ Enter roll number → Click **Remove**

4️⃣ Save Data  
→ Click **Save**

5️⃣ Load Data  
→ Click **Load**

<img width="549" height="614" alt="Screenshot 2025-10-23 131729" src="https://github.com/user-attachments/assets/5aba955b-6d43-49f0-8f48-2a82f8614fc8" />


---
