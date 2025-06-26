# 🧩 Spring Boot Level 1 - Maven Project

## 📄 Description - Exercise Statement

This project is part of the **Spring Framework Level 1** training.  
The goal is to create a basic **REST API** using **Spring Boot** and **Maven**, introducing concepts such as:

- HTTP protocol
- Dependency management using Maven
- REST controllers with Spring Boot
- Testing endpoints using Postman

### 📝 Exercise Summary

You must:

- Generate a Spring Boot project using https://start.spring.io with Maven and Java.
- Add the dependencies: `Spring Web` and `Spring Boot DevTools`.
- Set the server port to `9000`.
- Create a `HelloWorldController` with two GET endpoints:
  - One using `@RequestParam`
  - Another using an optional `@PathVariable`
- Test the application using Postman.
- Push the code to GitHub and provide two external learning resources.

---

## 💻 Technologies Used

- Java 11+
- Spring Boot (latest stable version)
- Maven
- Spring Web
- Spring Boot DevTools
- IntelliJ IDEA (or any Java IDE)
- Git + GitHub
- Postman

---

## 📋 Requirements

Before running the project, ensure you have:

- Java JDK 11 or newer installed
- Maven installed (`mvn -v` to verify)
- Git installed
- Internet connection to download Maven dependencies
- IntelliJ IDEA or another Java IDE (optional but recommended)

---

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/anaberod/S4.01_SpringFrameWork_Lv1.git
   cd S4.01_SpringFrameWork_Lv1
   ```

2. **Import into IntelliJ (if using an IDE):**
   - Open IntelliJ
   - Choose *File > Open* and select the project folder
   - IntelliJ will detect it as a Maven project

3. **Build the project:**
   ```bash
   mvn clean install
   ```

---

## ▶️ Execution

Run the project locally using:

```bash
mvn spring-boot:run
```

The server will start on:

```
http://localhost:9000
```

### Test endpoints with Postman or browser:

- `GET /HelloWorld`  
  → Returns: `Hola, UNKNOWN. Estás ejecutando un proyecto Maven`

- `GET /HelloWorld?nombre=Ana`  
  → Returns: `Hola, Ana. Estás ejecutando un proyecto Maven`

- `GET /HelloWorld2`  
  → Returns: `Hola, UNKNOWN. Estás ejecutando un proyecto Maven`

- `GET /HelloWorld2/Laura`  
  → Returns: `Hola, Laura. Estás ejecutando un proyecto Maven`

---

## 🌐 Deployment

This is a local training project and is **not deployed to production**.

If you wish to deploy it, you can:

- Package the app:
  ```bash
  mvn package
  ```
- Deploy the generated `.jar` file with:
  ```bash
  java -jar target/S04T01N01-0.0.1-SNAPSHOT.jar
  ```

---

## 🤝 Contributions

This project is part of a personal learning journey and is not open for external contributions.  
However, feel free to fork it or use it as reference.

If you wish to contribute:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes
4. Push to your fork
5. Open a pull request

---
