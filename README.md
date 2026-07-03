# Full Stack Java CRUD Application

A Full Stack Java web application that demonstrates **CRUD (Create, Read, Update, Delete)** operations using **Java, JSP, Servlets, JDBC, and MySQL**. This project follows the MVC architecture and provides a simple, responsive interface for managing records while showcasing database connectivity and Java web development concepts.

---

## 🚀 Features

- ➕ Add new records
- 📋 View all records
- ✏️ Update existing records
- ❌ Delete records
- 🔗 JDBC connectivity with MySQL
- 🏗️ MVC architecture (Model-View-Controller)
- ✅ Input validation
- 💻 Responsive user interface

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- JSP

### Backend
- Java
- Servlets
- JDBC

### Database
- MySQL

### Tools
- Eclipse IDE
- Apache Tomcat
- MySQL Workbench
- Git & GitHub

---

## 📂 Project Structure

```
full-stack-java-app/
│
├── src/
│   ├── controller/
│   ├── dao/
│   ├── model/
│   └── utility/
│
├── WebContent/
│   ├── css/
│   ├── js/
│   ├── images/
│   ├── index.jsp
│   ├── add.jsp
│   ├── edit.jsp
│   └── view.jsp
│
├── README.md
└── .gitignore
```

> Folder names may vary depending on your Eclipse project structure.

---

## ⚙️ Prerequisites

Before running the project, make sure you have:

- Java JDK 8 or later
- Eclipse IDE (Enterprise Edition recommended)
- Apache Tomcat
- MySQL Server
- MySQL Connector/J

---

## 📥 Installation

### 1. Clone the repository

```bash
git clone https://github.com/gitvaibhavi/full-stack-java-app.git
```

### 2. Import into Eclipse

```
File
→ Import
→ Existing Projects into Workspace
```

### 3. Create the Database

```sql
CREATE DATABASE fullstack_java;
USE fullstack_java;
```

Create the required table(s) according to your project.

---

### 4. Configure Database Connection

Update your JDBC connection details.

```java
String url = "jdbc:mysql://localhost:3306/fullstack_java";
String username = "root";
String password = "your_password";
```

---

### 5. Add MySQL Connector

```
Project
→ Build Path
→ Configure Build Path
→ Add External JARs
```

Select the downloaded **mysql-connector-j** JAR file.

---

### 6. Run the Project

Deploy the project on Apache Tomcat and open:

```
http://localhost:8080/full-stack-java-app/
```

---

## 📌 CRUD Operations

| Operation | Description |
|----------|-------------|
| Create | Add new records |
| Read | Display all records |
| Update | Modify existing records |
| Delete | Remove records from the database |

---

## 💡 Learning Outcomes

This project demonstrates:

- Java Web Development
- JSP & Servlets
- JDBC Connectivity
- MySQL Integration
- MVC Architecture
- CRUD Operations
- Form Handling
- Exception Handling
- Database Operations

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is created for educational and learning purposes.

---

## 👩‍💻 Author

**Vaibhavi Parmar**

- GitHub: https://github.com/gitvaibhavi
- LinkedIn: https://www.linkedin.com/in/parmar-vaibhavi-368080297/

---

## ⭐ Show Your Support

If you found this project helpful, please consider giving it a **⭐ Star** on GitHub.

Happy Coding! 🚀
