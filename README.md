🏥 Hospital Management System
📘 Overview

The Hospital Management System is a web-based application built using Java Servlets and JSP to simplify and automate hospital operations such as patient management, doctor scheduling, appointments, billing, and medical records.
It provides separate modules for administrators, doctors, and patients to enhance efficiency and streamline hospital workflows.

🚀 Features

👨‍⚕️ Admin Panel

Manage doctors, patients, appointments, and medical records

View and delete records

🧑‍⚕️ Doctor Dashboard

View patient appointments and update treatment status

🏥 Patient Portal

Register, book or cancel appointments, and view billing details

💊 Medical Record Management

Add and view patient medical history

💰 Billing System

Automatic bill generation for treatments and appointments

🔐 Authentication System

Secure login for admin, doctor, and patient roles

🧩 Technologies Used
Category	Tools/Technologies
Frontend	JSP, HTML, CSS
Backend	Java Servlets
Database	XML (or MySQL if extended)
Server	Apache Tomcat
Build Tool	Maven
IDE	IntelliJ IDEA / VS Code / Eclipse
⚙️ Project Structure
Hospital-Management-System/
├── src/
│   ├── main/
│   │   ├── java/com/hospital/
│   │   │   ├── dao/        # Data Access Layer
│   │   │   ├── model/      # POJO Classes
│   │   │   └── servlets/   # Controllers
│   │   └── webapp/         # JSP Pages, CSS
│   └── test/               # (Optional: Unit Tests)
├── data/                   # XML files for data storage
├── pom.xml                 # Maven configuration
└── README.md

🧠 How It Works

Patient registers and logs in via JSP form.

Admin adds doctors and manages patient details.

Patients book appointments with available doctors.

Doctors update treatment records, which are stored in the system.

Bills are generated automatically for each completed appointment.

🛠️ Setup & Installation

Clone the repository:

git clone https://github.com/parass06/Hospital-Management-System.git


Open the project in your IDE (VS Code / IntelliJ / Eclipse).

Make sure you have Apache Tomcat installed and configured.

Build the project using Maven:

mvn clean install


Deploy the .war file or run directly on Tomcat.

Open your browser and go to:

http://localhost:8080/Hospital-Management-System/

🧾 Future Enhancements

Database migration from XML → MySQL

Role-based dashboards with analytics

Integration with email/SMS notifications

RESTful APIs for mobile app integration
