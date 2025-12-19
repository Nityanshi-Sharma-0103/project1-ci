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



## 📸 Project Screenshots

### Jenkins Setup
![Jenkins Welcome](screenshots/01-jenkins-welcome.png)
![Jenkins Installed](screenshots/02-jenkins-installed.png)
![Admin User](screenshots/03-jenkins-admin-user.png)
![Users](screenshots/04-jenkins-users.png)

### Infrastructure
![GCP Jenkins VM](screenshots/05-gcp-jenkins-vm.png)
![CI Server](screenshots/06-gcp-ci-server.png)
![Server Details](screenshots/07-ci-server-details.png)

### Development
![Java Code](screenshots/08-java-code-vscode.png)
![Local Build](screenshots/09-local-java-build.png)

### Jenkins CI
![Build](screenshots/10-jenkins-build.png)
![Workspace](screenshots/11-jenkins-workspace.png)
![Target Folder](screenshots/12-jenkins-workspace-target.png)

### Logs
![Console Output](screenshots/13-jenkins-console-output.png)
![Build Success](screenshots/14-jenkins-console-success.png)

### Application Running
![Spring Boot on Ubuntu](screenshots/15-springboot-running-ubuntu.png)
![App in Browser](screenshots/16-springboot-running-browser.png)
