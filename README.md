 Java-based Hospital Management System that enables efficient management of patient and doctor records using a MySQL database.

✨ Features

🔹 Add Patients – Store patient details like name, age, and gender.

🔹 View Patients – Display all registered patients in a tabular format.

🔹 Search Patient by ID – Retrieve patient details by their unique ID.

🔹 View Doctors – List all available doctors along with their specialization.

🔹 Search Doctor by ID – Retrieve doctor details by their unique ID.

🚀 Getting Started

1️⃣ Prerequisites

Ensure you have the following installed:

Java Development Kit (JDK 8+)

MySQL Database

JDBC Driver for MySQL

2️⃣ Database Setup

Create a MySQL database and required tables:

CREATE DATABASE HospitalDB;
USE HospitalDB;

CREATE TABLE patients (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    age INT NOT NULL,
    gender VARCHAR(10) NOT NULL
);

CREATE TABLE doctors (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    specialization VARCHAR(50) NOT NULL
);

🎯 How to Run

1️⃣ Compile the Java Files

javac -d . *.java

2️⃣ Run the Program

java HospitalManagementSystem.Main

📌 Future Enhancements

✅ Implement an Appointment System

✅ Add a Billing Module

✅ Develop a GUI Interface for better user interaction

🤝 Contribution

Want to improve this project? Feel free to fork and contribute! 🚀

🔗 GitHub Repository: https://github.com/desaishro/medcare
