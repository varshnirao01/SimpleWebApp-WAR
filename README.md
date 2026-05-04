# 🎵 SimpleWebApp (WAR Deployment using JSP & Tomcat)

## 📌 Project Overview

This is a simple Java web application built using **JSP (Java Server Pages)** and deployed on **Apache Tomcat** using a **.war file**.
The project demonstrates basic web app structure and deployment workflow.

---

## 🛠️ Technologies Used

* Java (JDK 21 / OpenJDK)
* JSP (Java Server Pages)
* Apache Tomcat 9
* GitHub (Version Control)
* Jenkins (for CI/CD - optional)

---

## 📂 Project Structure

```
SimpleWebApp/
│
├── index.jsp
├── hello.jsp
├── WEB-INF/
│   └── web.xml
└── SimpleWebApp.war
```

---

## 🚀 How to Run the Project

### 1️⃣ Install Requirements

* Install Java (JDK)
* Download Apache Tomcat

---

### 2️⃣ Deploy WAR File

1. Copy `SimpleWebApp.war`
2. Paste into:

```
apache-tomcat-9.0.xx/webapps/
```

---

### 3️⃣ Start Tomcat

* Go to:

```
apache-tomcat-9.0.xx/bin/
```

* Run:

```
startup.bat
```

---

### 4️⃣ Open in Browser

```
http://localhost:9090/SimpleWebApp
```

---

## 📸 Output Pages

* `index.jsp` → Home page
* `hello.jsp` → Sample response page

---

## ⚙️ CI/CD Integration (Optional)

This project can be integrated with **Jenkins**:

* Pull code from GitHub
* Automatically deploy WAR file to Tomcat
* Enable continuous delivery

---

## 🎯 Learning Outcome

* Understanding WAR file structure
* Deploying Java web apps on Tomcat
* Basic CI/CD pipeline using Jenkins

---

## 👤 Author

**Vansh Malraj**

---

## ⭐ Notes

* Make sure Tomcat is running
* Ensure correct port (default: 8080 or changed: 9090)
* Set JAVA_HOME if required

---
