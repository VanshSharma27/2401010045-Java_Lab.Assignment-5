# 2401010045-Java_Lab.Assignment-5
This Java program manages student records using file handling. It lets users add, view, search, delete, and sort students by marks. Data is stored in a text file as CSV. The program loads existing records at startup and saves all updates on exit using a menu-driven console interface.

# 📚 Student Record Management System  
*A Java Console Application using OOP + File Handling + Collections*

This project is a **menu-driven Student Record Management System** built using **Java**, designed to store and manage student details using **text file persistence**.  
It demonstrates core concepts of:

- Object-Oriented Programming  
- Java File Handling (`FileReader`, `BufferedReader`, `BufferedWriter`, `RandomAccessFile`)  
- Collections (`ArrayList`)  
- Exception handling  
- CSV-style data storage  

---

## 🚀 Features

### ✅ Add Student  
Input Roll No, Name, Email, Course, and Marks. Data is validated and stored as an object.

### ✅ View All Students  
Displays all stored records in a neat, readable format.

### ✅ Search Student by Name  
Case-insensitive search across all student records.

### ✅ Delete Student by Name  
Deletes the first matching student using `removeIf()`.

### ✅ Sort Students by Marks  
Sorts records in **descending order** using a custom comparator.

### ✅ Save and Exit  
Automatically writes all student data to `students.txt` in CSV format.


---

## 🧠 Class Overview

### 🔸 **StudentData**
- Represents each student  
- Supports:
  - `toString()`  
  - `toCSV()`  
  - `fromCSV()`  

### 🔸 **StudentFileHandler**
- Reads students from file  
- Writes updated records  
- Reads specific lines using `RandomAccessFile`  

### 🔸 **StudentRecordController**
- Add, View, Search, Delete, Sort, Save  
- Holds student list in `ArrayList<StudentData>`  

### 🔸 **LabAssignment5 (Main Program)**
- Displays menu  
- Accepts user input  
- Calls controller functions  

---

## 🖥️ How to Run

### 1️⃣ Compile the program  
```bash


## 🗂️ Project Structure
