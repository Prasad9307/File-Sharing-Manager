# File Sharing Management System

[![Java](https://img.shields.io/badge/Language-Java-blue.svg)](https://www.java.com/)  
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.3.3-green.svg)](https://spring.io/projects/spring-boot)  
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🚀 Overview

The **File Sharing Management System** is a secure and efficient Java-based web application for managing file uploads, downloads, and sharing. This system leverages **Spring Boot**, **MySQL**, **HTML**, **CSS**, **SQL**, and **Thymeleaf** for a seamless experience.

---

## ✨ Features

- **File Upload & Download**: Simplify file management.
- **Secure Sharing**: Powered by OAuth2 and Spring Security.
- **Database Integration**: Uses MySQL for persistent storage.
- **Web Interface**: Built with Thymeleaf templates for responsive and intuitive UI.

---

## ⚙️ Requirements

Ensure the following are installed before running the application:

- **Java JDK 17 or higher**
- **Apache Maven 3.6+**
- **MySQL Database**

---

## 🛠️ Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/file-sharing-management.git
cd file-sharing-management
```

### 2️⃣ Configure the Application

Update the `application.properties` file in `src/main/resources/`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=your_username
spring.datasource.password=your_password
```

### 3️⃣ Build and Run the Application

Run the following commands:

```bash
mvn clean install
mvn spring-boot:run
```

### 4️⃣ Access the Application

Open your browser and navigate to:  
`http://localhost:8080`

---

## 📸 Screenshots

### Home Page  
![Home Page](https://github.com/Prasad9307/File-Sharing-Manager/blob/main/src/1.PNG)

### File Login Page  
![File Login Page](https://github.com/Prasad9307/File-Sharing-Manager/blob/main/src/2.PNG)

### File Upload Page  
![File Upload Page](
https://github.com/Prasad9307/File-Sharing-Manager/blob/main/src/3.PNG)

### File Download Page  
![File Download Page](https://github.com/Prasad9307/File-Sharing-Manager/blob/main/src/4.PNG)

_Add your actual screenshots to the `screenshots/` folder and link them here._

---

## 📂 Project Structure

```plaintext
file-sharing-management/
├── src/
│   ├── main/
│   │   ├── java/com/yourcompany/filesharing/
│   │   │   ├── configuration/   # Configuration files
│   │   │   ├── controller/      # REST Controllers
│   │   │   ├── entity/          # Data entities
│   │   │   ├── service/         # Business logic
│   │   │   ├── repository/      # Database repositories
│   │   └── resources/
│   │       ├── static/          # CSS, JS, and images
│   │       ├── templates/       # Thymeleaf templates
│   │       └── application.properties
│   └── test/                    # Unit tests
├── pom.xml                      # Maven dependencies
└── README.md                    # Documentation
```

---

## 🤝 Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a feature branch:  
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:  
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:  
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 📞 Contact

For queries or suggestions, feel free to reach out:

- **Email**: prasadpawar.nbnstic.it@gmail.com 
- **GitHub**:(https://github.com/Prasad9307)  
- **LinkedIn**:(https://www.linkedin.com/in/prasad-pawar1)

---

## 🌟 Special Thanks

Special thanks to **[Coding Wallah Sir YT Channel](https://youtu.be/3Fam-U_wQag?si=7Ujn8NBFhOhjWtlx)** for inspiring and guiding this project.

---

## 🧰 Technical Skills

- **Java** (Java SE & EE)
- **Spring Boot** (Spring MVC, Spring Security)
- **Thymeleaf** (Template engine for web applications)
- **MySQL** (Database management)
- **OAuth2** (Authentication & Authorization)
- **HTML, CSS, and JavaScript** (Web front-end development)
- **Maven** (Build automation)
- **Git** (Version control)

---
```

You can copy and paste this directly into your `README.md` file. Let me know if you'd like to make further adjustments!
