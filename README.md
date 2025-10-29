# 🎓 Student Information Management System

A **Java-based web application** to manage student records, allowing users to log in, update their profile, view other users (admin only), and reset passwords.  

---

## 🚀 Features
- Register and log in securely using email and password  
- Update personal details (name, phone, branch, location, etc.)  
- View all users (Admin only)  
- Reset password functionality  
- Session management for secure access  

---

## 🧰 Tech Stack

| Layer | Technology Used |
|-------|------------------|
| **Frontend** | JSP, HTML5, CSS3, Bootstrap |
| **Backend** | Java Servlets, JDBC |
| **Database** | MySQL |
| **Server** | Apache Tomcat 10 |
| **IDE** | Eclipse IDE |

---

## 🧩 Project Structure

StudentDynamicProject/
├── src/
│ ├── com/student/dynamic/ # Servlets (Login, Logout, Update, ResetPassword)
│ ├── com/pentagon/StudentDAO/ # DAO interfaces and implementations
│ ├── com/pentagon/StudentDTO/ # Student model class
│ └── com/pentagon/DB/ # Database connection class
│
├── WebContent/
│ ├── dashboard.jsp
│ ├── login.jsp
│ ├── update.jsp
│ ├── resetPassword.jsp
│ ├── view_user.jsp
│ └── css/, js/, images/ (optional)


---

## 🛠️ How to Run

1. Install **Apache Tomcat 10** and **MySQL Server**  
2. Create a database named `studentdb`  
3. Import your SQL schema file (e.g., `student.sql`)  
4. Update the database connection details in your connector class  
5. Deploy the project to Tomcat through **Eclipse IDE**  
6. Access the app at:  


---

## 👩‍💻 Author

**S. Ramya Saraswathi**  
📎 [LinkedIn](https://www.linkedin.com/in/ramyasaraswathi)  
💻 [GitHub](https://github.com/Ramya-Saraswathi123)

---

## 📜 License
This project is open-source and free to use for educational purposes.
