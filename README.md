<h1 align="center">🏥 Hospital Management System</h1>

<p align="center">
  <b>A Web Application using Java Servlets & JSP for Efficient Hospital Administration</b><br>
</p>

---

## 📘 Overview
The **Hospital Management System** is a full-stack Java web application designed to simplify hospital operations such as managing patients, doctors, appointments, billing, and medical records.  
It provides secure role-based access for **Admins**, **Doctors**, and **Patients**, ensuring an organized and efficient healthcare workflow.

---

## 🚀 Features
✅ **Admin Panel**
- Manage doctors, patients, appointments, and records  
- Add or delete users and view system data  

✅ **Doctor Dashboard**
- View scheduled appointments  
- Update patient treatment details and statuses  

✅ **Patient Portal**
- Register, book, or cancel appointments  
- View bills, prescriptions, and medical records  

✅ **Medical & Billing Management**
- Store and retrieve patient medical history  
- Auto-generate bills for treatments and consultations  

✅ **Secure Login System**
- Separate login modules for Admin, Doctor, and Patient  

---

## 🧩 Tech Stack

| Category | Technologies |
|-----------|--------------|
| **Frontend** | JSP, HTML, CSS |
| **Backend** | Java Servlets |
| **Database** | XML (extendable to MySQL) |
| **Server** | Apache Tomcat |
| **Build Tool** | Maven |
| **IDE** | IntelliJ IDEA / VS Code / Eclipse |

---

## 🧠 How It Works
1. **Patients register** and log in to manage appointments.  
2. **Admins add doctors**, manage data, and oversee activities.  
3. **Doctors update patient details** and medical records.  
4. **System auto-generates bills** and stores treatment data securely.

---

## 🛠️ Setup & Installation

### Prerequisites
- Java JDK (8 or higher)  
- Apache Tomcat  
- Maven  

### Steps
```bash
# Clone this repository
git clone https://github.com/parass06/Hospital-Management-System.git

# Navigate into the project
cd Hospital-Management-System

# Build the project
mvn clean install
```

Then, deploy on Tomcat or run directly via your IDE.
Finally, open your browser at: http://localhost:8080/Hospital-Management-System/

Future Enhancements

✅ Switch from XML to MySQL database

📊 Add dashboard analytics for admin

📩 Email/SMS appointment notifications

📱 REST API for mobile integration
