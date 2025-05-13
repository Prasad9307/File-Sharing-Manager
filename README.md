It seems like you want to modify the README to reflect a version of the project without Spring Boot. Here's the updated version based on your original request:

````markdown
# File Sharing Management System

[![Java](https://img.shields.io/badge/Language-Java-blue.svg)](https://www.java.com/)  
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🚀 Overview

The **File Sharing Management System** is a secure and efficient Java-based application for managing file uploads, downloads, and sharing. This system leverages **Java**, **MySQL**, **HTML**, **CSS**, **JDBC**, and **Servlets** for a seamless experience.

---

## ✨ Features

- **File Upload & Download**: Simplify file management.
- **Secure Sharing**: Powered by **Java Authentication**.
- **Database Integration**: Uses **MySQL** for persistent storage.
- **Web Interface**: Built with **HTML** and **CSS** for a responsive and intuitive UI.

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
````

### 2️⃣ Configure the Application

Update the `db.properties` file in the `src/main/resources/` folder:

```properties
db.url=jdbc:mysql://localhost:3306/your_database
db.username=your_username
db.password=your_password
```

### 3️⃣ Build and Run the Application

Run the following commands:

```bash
mvn clean install
mvn exec:java
```

### 4️⃣ Access the Application

The application will run locally. Access the UI via the following link:
`http://localhost:8080`

---

## 📸 Screenshots

### Home Page

![Home Page](https://github.com/Prasad9307/File-Sharing-Manager/blob/main/src/1.PNG)

### File Login Page

![File Login Page](https://github.com/Prasad9307/File-Sharing-Manager/blob/main/src/2.PNG)

### File Upload Page

![File Upload Page](https://github.com/Prasad9307/File-Sharing-Manager/blob/main/src/3.PNG)

### File Download Page

![File Download Page](https://github.com/Prasad9307/File-Sharing-Manager/blob/main/src/4.PNG)

*Add your actual screenshots to the `screenshots/` folder and link them here.*

---

## 📂 Project Structure

```plaintext
file-sharing-management/
├── src/
│   ├── main/
│   │   ├── java/com/yourcompany/filesharing/
│   │   │   ├── configuration/   # Configuration files
│   │   │   ├── controller/      # File handling logic
│   │   │   ├── entity/          # Data entities
│   │   │   ├── service/         # Business logic
│   │   │   ├── repository/      # Database repositories
│   │   └── resources/
│   │       ├── static/          # CSS, JS, and images
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

* **Email**: [prasadpawar.nbnstic.it@gmail.com](mailto:prasadpawar.nbnstic.it@gmail.com)
* **GitHub**: [https://github.com/Prasad9307](https://github.com/Prasad9307)
* **LinkedIn**: [https://www.linkedin.com/in/prasad-pawar1](https://www.linkedin.com/in/prasad-pawar1)

---

## 🌟 Special Thanks

Special thanks to **[Coding Wallah Sir YT Channel](https://youtu.be/3Fam-U_wQag?si=7Ujn8NBFhOhjWtlx)** for inspiring and guiding this project.

---

## 🧰 Technical Skills

* **Java** (Java SE)
* **MySQL** (Database management)
* **HTML, CSS, and JavaScript** (Web front-end development)
* **JDBC** (Java Database Connectivity)
* **Maven** (Build automation)
* **Git** (Version control)

---

```

You can now use this version of the README file for your project!
```
