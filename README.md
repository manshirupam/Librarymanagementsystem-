# 📚 Java Spring Boot - Library Management System

A comprehensive Library Management System built with Java and Spring Boot. This application provides a web-based interface to manage library operations, including tracking books, authors, publishers, and categories.

## 🚀 Features

- **Authentication & Authorization**: Secure admin login interface using Spring Security.
- **Book Management**: Add, update, view, and delete book records.
- **Author Management**: Maintain a database of authors with full CRUD capabilities.
- **Category Management**: Organize books into different categories.
- **Publisher Management**: Keep track of publishers and their details.
- **Data Export**: Export data to CSV and PDF formats (powered by OpenCSV and iTextPDF).

## 🛠️ Tech Stack

- **Backend**: Java 17, Spring Boot 2.6.4, Spring Data JPA, Spring Security
- **Frontend**: Thymeleaf (Server-side rendering), HTML/CSS
- **Database**: H2 Database (In-memory)
- **Export Capabilities**: OpenCSV, iTextPDF

## ⚙️ Local Setup Instructions

Follow these steps to run the project locally on your machine:

1. **Clone the repository** (or download the source code):
   ```bash
   git clone <https://github.com/manshirupam/Librarymanagementsystem->
   ```

2. **Prerequisites**:
   - Ensure you have [JDK 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html) installed.
   - Ensure you have [Apache Maven](https://maven.apache.org/install.html) installed.

3. **Build the project**:
   Navigate to the project root directory and run:
   ```bash
   mvn clean install
   ```

4. **Run the application**:
   ```bash
   mvn spring-boot:run
   ```

5. **Access the application**:
   Open your browser and navigate to: `http://localhost:9080`

6. **Admin Login Credentials**:
   - **User ID**: `admin@admin.in`
   - **Password**: `Temp123`

---

## 📄 License

This project is open-source and available under the terms of the included LICENSE.
