
# Telit Interview Assignment

# 🎓 Student Management System (Java Console Application)

A simple **console-based Java (JDK 11)** application to manage student information, including validation, course enrollment, and data display.

---

## 🚀 Features

- ✅ Create Student with validations
- ✅ Validate:
  - Name (alphabets only)
  - Age (19–35 range)
  - Student ID (Format: `S-123`)
- ✅ Enroll student in courses
- ✅ Prevent duplicate course enrollment
- ✅ Display student details
- ✅ Clean and modular code with validation methods

---

## 🛠️ Tech Stack

- Java 11
- Core Java Concepts:
  - OOP (Encapsulation, Constructor)
  - Collections (`ArrayList`)
  - Regex (`Pattern`, `Matcher`)

---

## 📂 Project Structure
```
StudentManagementSystem/
│
├── src/
│ └── com/
│ └── studentapp/
│ └── Main.java
│ └── Student.java
│
└── README.md
```
---

## 📌 Validations Implemented

| Field        | Rule |
|-------------|------|
| Name        | Only alphabets and spaces |
| Age         | Between 19 and 35 |
| Student ID  | Must follow format `S-<number>` |
| Courses     | Allowed: Java, DSA, Devops |

---

## 🎯 Supported Courses

- JAVA  
- DSA  
- Devops  

---

## 🧪 Sample Usage

```java
package com.studentapp;

public class Main {
    public static void main(String[] args) {

        Student student = new Student("Karan", 25, "S-101");

        student.enrollCourse("Java");
        student.enrollCourse("DSA");
        student.enrollCourse("Java"); // Duplicate

        student.printStudentInfo();
    }
}
```
---
## ⚙️ How to Run
🔹 Prerequisites

 - Java JDK 11 installed

 - Any IDE (IntelliJ / Eclipse / VS Code) or terminal

🔹 Steps

 1. Clone the repository

    ``` git clone https://github.com/your-username/student-management-system.git ```

 2. Navigate to project folder
 
    ``` cd student-management-system ```

 3. Compile the code

    ``` javac com/studentapp/*.java ```

 4. Run the program

    ``` java com.studentapp.Main ```

---
## 🧑‍💻 Author

**Karan Sagale**

SDET | Automation QA Engineer

7 Years Experience (Manual + Automation Testing)

## 🔗 Links

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://karan-sagale.github.io/)  
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karan-sagale-qa/)  
            
