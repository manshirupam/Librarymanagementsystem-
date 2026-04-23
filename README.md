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
   git clone <repository-url>
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

## 📸 Screenshots

### Admin Login Interface
Secure access control for library administrators.
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiiuctxupeOK4Nh8j-nomwwapjkcVvkYig3lX7qoifcXE76_6CnOXMZ-CLww7G180qegsCkrtyUlaqpJsWm9GzhX9QUFxyNyEUAXFD5UWJpvh2BdIr0wyAnFC38QOdsL_1vak8LtxYHrZyplCU_Sri-7kM9nXxI9heXXB0621rzJgL6j1CSweX6xjaorg/s945/admin-login.png" width="100%">

### Book Management (Add, Update, View, Delete)
Manage the library's book inventory easily.
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjYMpuCQx3lGsS4T_H4ziyDWIkBpYV5qgo5JHFMV0Drper48H7YfygEdv0htE3yWo8mlypUW9W7NFY00UtrVznFfFYIzNGAXBeskhBb_kHAJrVKnI7O5mZt0_c085n6ir-cNVEYsTYffn6WgCmoBiZULR88ah_YxDC-ywRKPTsxj58GcHFnyyeX00RsNA/s800/library-management-system.png" width="100%">

### Author Management (Add, Update, View, Delete)
Maintain detailed records of all authors.
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEixAW5k4E9IXf_OuVO1S5m100KS1xFo2ZrFoLnZYvNLjfpmIdI8W0ukd6yQn6oTsSWBKjDdAIGsnPf0EhgRwKzfpVq3mJXMcqG94Qp2oCCy0Pzf01b3kXP2ahgbvpFQND60c7cHwPNZ7A6uXh7fxqvB5od26PleS3giunEN-uAuFIuKijjELspH1_gLcw/s934/authors-list.png" width="100%">

### Category Management (Add, Update, View, Delete)
Organize books into various specific categories.
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhYe6-eBO4HZjqE1Rr0PLoHS1dlvlnwuagwQtX6eRavoDsWRGk4yfguhWIdcOFRgM4H7985xL1bdiLQLqX_iU7RzddDb1yiQ0P3M0sfwUdTRlRGMg85Kp2KKTsVZH5WGlptL6LFRTITq4oSCJFFCZwGML1RrxI-chu-xb4eXOWIoZpNlFWLLUzkW6zLdQ/s935/categorylist.png" width="100%">

### Publisher Management (Add, Update, View, Delete)
Keep track of book publishers and their information.
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhcNQAd4UVi_bYQQSvW49hn0rQ1O7bEBDyN4DDNJSH1rtxBg37QIHQKAp7ELGbFV4Xva2F0DmhTkA3vKVeZcmKs7lODgTulsJr1aLyBckEojzxzZE5FYlfuEwD62Qco6PsjdNVPEWT76GlyVnSP94zNZK59w3CMRuvbYjoc1-MpyXj-WCeNEjPDm6mucw/s938/publishers-list.png" width="100%">

## 📄 License

This project is open-source and available under the terms of the included LICENSE.
