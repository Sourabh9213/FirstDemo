# 🚀 Automation Test Framework with Jenkins, Docker & Git

## 📌 Project Overview

This project is an automation testing framework integrated with Jenkins, Docker, and Git.
It is designed to run test cases automatically using CI/CD pipeline.

---

## 🛠️ Technologies Used

* Java
* Selenium WebDriver
* TestNG
* Maven
* Jenkins
* Docker
* Git & GitHub

---

## ⚙️ Project Setup

### 1. Clone the Repository

```bash
git clone <your-repo-link>
cd <project-folder>
```

---

### 2. Build the Project

```bash
mvn clean install
```

---

### 3. Run Tests

```bash
mvn test
```

---

## 🔁 CI/CD Integration (Jenkins)

* Jenkins is configured to pull code from GitHub
* Maven build is triggered using:

  ```
  clean test
  ```
* Test execution happens automatically on build

---

## 🐳 Docker Integration

* Docker is used to run the project in a containerized environment
* Helps in maintaining consistency across different systems

### Docker Steps:

```bash
docker build -t automation-project .
docker run automation-project
```

---

## 🔗 Git Integration

* Source code is managed using GitHub
* Jenkins is connected to GitHub repository
* Automatic build triggers on code changes

---

## 📊 Features

* Automated test execution
* CI/CD pipeline using Jenkins
* Docker container support
* Easy project setup using Maven

---

## 📌 Conclusion

This project demonstrates how DevOps tools like Jenkins, Docker, and Git can be integrated with an automation framework to achieve continuous testing and faster delivery.

---

## 👨‍💻 Author  
Sourabh  
(Documentation assisted with AI tools)
