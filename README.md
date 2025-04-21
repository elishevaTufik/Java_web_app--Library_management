# 📚 Library Management System – Java Web Application

A Java-based web application for managing a library system. Built using the MVC architecture with a DAO layer for database access, and Servlets as controllers. The project includes modules for managing books, students, staff, and internal messaging.

---

## ✨ Key Features

- 📘 Manage books – add, edit, delete, search
- 👩‍🎓 Manage students – register, update, delete
- 🧑‍💼 Manage staff and teachers
- 💬 Internal messaging system
- 📊 Clean MVC structure
- 🗃️ DAO layer for all database operations

---

## 🧱 Project Structure

```bash
src/
└── main/
    └── java/
        └── Registration/
            ├── controller/      # Servlets
            ├── dao/             # DAO layer
            └── model/           # Entity classes
```

- **Model**: `Book.java`, `Student.java`, `Worker.java`, `Msg.java`, `Teacher.java`  
- **DAO**: `BookDao.java`, `StudentDao.java`, `WorkerDao.java`, `MsgDao.java`  
- **Controllers**: `BookServlet.java`, `StudentServlet.java`, `WorkerServlet.java`, `MsgServlet.java`  

---

## ⚙️ Technologies Used

- Java (JDK 8+)
- Java Servlets
- JSP / HTML / CSS
- JDBC
- MVC + DAO Design Patterns
- Apache Tomcat (for deployment)

---

## 🚀 How to Run

1. **Import the project into an IDE** – like IntelliJ or Eclipse
2. **Configure Apache Tomcat server**
3. **Connect to a database (e.g., MySQL)**
4. **Run via Tomcat and access through your browser**

---

## 🛠 Requirements

- JDK 8 or higher
- Apache Tomcat
- MySQL (or equivalent database)
- Java IDE (IntelliJ / Eclipse)

---

## 📄 License

This project was developed as a self-learning exercise in Java web technologies and is open for educational use.

---

## 🙋‍♀️ Developed by

Elisheva Tufik  
Software developer with a love for structure, clarity, and maintainable code 😊
