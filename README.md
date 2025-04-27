
---

# 🎓 College For Research and Technology - Student Information System (Java NetBeans)

## 📌 Project Overview
The **Student Information System** is a desktop application built using **Java** and **NetBeans IDE**.  
It allows administrators to manage student data, including **adding**, **updating**, **deleting**, **printing**, and **searching** student records such as **Name**, **Section**, and **Subject**.

The system includes **navigation menus** for better organization and an **Admin Login** system to secure access.

---

## 🛠️ Features

### 👨‍🎓 Student Management (CRUD)
- **Create** new student records (Name, Section, Subject)
- **View** student records
- **Update** existing student information
- **Delete** student records
- **Print** selected student information
- **Search** student by Name, Section, or Subject

### 🧭 Navigation Menu
- **Home:** Welcome page
- **Contact:** School contact information
- **Course:** List of available courses
- **Data:** Manage student records (CRUD operations)
- **Logout:** Return to the Admin Login page

### 🔒 Admin Login
- Only authorized admins can access the system.
- **Login Credentials:**
  - **Username:** `Admin`
  - **Password:** `Admin123`
- Logout securely to protect the system.

---

## 📚 Technologies Used
- **Java** (Core Java + Swing for GUI)
- **NetBeans IDE** (for development)
- **No external database** (Data is handled locally)

---

## 🧩 How to Run the Project

### 1. Requirements
- Install **Java JDK** (version 8 or above)
- Install **NetBeans IDE**

### 2. Setup
- Download or clone the project files.
- Open **NetBeans IDE**.
- Navigate to:
  ```
  File ➔ Open Project ➔ Select the project folder
  ```

### 3. Running the Project
- Press **Shift + F6** or click **Run ➔ Run Project** inside NetBeans.
- Login using:
  - **Username:** `Admin`
  - **Password:** `Admin123`

---

## 📋 Example Student Fields
| Field     | Description                        |
|-----------|-------------------------------------|
| Name      | Full name of the student            |
| Section   | Section name or number (e.g., BSIT-1A) |
| Subject   | Subject enrolled (e.g., Mathematics, IT Fundamentals) |

---

## ⚡ Important Notes
- Make sure to **enter correct login credentials** to access the system.
- Data is **temporary** unless additional saving methods are implemented.
- "Print" can show student details in a new window, in the console, or connect to a real printer if extended.

---

## 🎯 Future Improvements (Optional)
- Add **file saving** or **database** support for permanent data storage
- Improve UI design with **JavaFX** or custom themes
- Add **PDF Export** feature for student records
- Implement **multiple user roles** (Admin, Staff)

---

> ✨ **Tip:** Always secure your Admin credentials and consider encrypting passwords for a production-level system.

---