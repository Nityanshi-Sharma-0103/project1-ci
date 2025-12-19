# Jenkins CI Pipeline – Spring Boot PetClinic

## 📌 Project Overview
This project demonstrates a complete **Continuous Integration (CI)** workflow using **Jenkins**, **Maven**, and a real-world **Spring Boot application (PetClinic)**.

The objective was to build, package, and run an enterprise-grade Java application using Jenkins.

---

## 🛠️ Tech Stack
- Jenkins
- Maven
- Java (JDK 25)
- Spring Boot (PetClinic)
- GitHub
- Google Cloud (Compute Engine)

---

## ⚙️ CI Workflow
1. Code hosted on GitHub
2. Jenkins pulls source code
3. Maven resolves dependencies
4. Application is compiled & packaged
5. Executable JAR is generated
6. JAR is executed on VM
7. Application accessed via browser

---

## 📂 Build Artifact:

---


---

## 🚀 Application Running
The Spring Boot application runs on port **8083**.


---

## 📸 Screenshots
Below are screenshots captured during the project execution:

- Jenkins build success
- Jenkins console output
- Generated JAR file in workspace
- Application running in browser

(see `/screenshots` folder)

---

## 🧠 Key Learnings
- Difference between **compile vs build**
- Maven lifecycle in real-world projects
- Jenkins workspace & artifacts
- Running Spring Boot JARs
- CI is more than just “BUILD SUCCESS”

---

## 🔮 Future Enhancements
- Jenkinsfile (Pipeline as Code)
- Dockerizing the application
- Automated deployment (CD)
- GitHub webhook integration

project1-ci/
├── README.md
├── screenshots/
│   ├── jenkins-build-success.png
│   ├── console-output.png
│   ├── app-running-browser.png


After successful build, Jenkins generates:

