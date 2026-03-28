# 🔗 Java Batch Final Project – Milestone Four

## 🔗 Project Description
This project is a **Java-based Test Automation Framework** developed as part of the Java Batch Milestone assessment.  
It follows **Agile methodology**, uses **Maven** for dependency management, and implements the **Page Object Model (POM)** design pattern.

---

## 🔗 Methodology
**Agile Methodology** was followed throughout the project lifecycle.

Development was carried out iteratively across multiple sprints including:
- Requirement analysis  
- Framework setup  
- Test implementation  
- Execution and documentation  

Sprint-wise execution with dates is documented in 🔗 **AGILE.md**.

---

## 🔗 Technology Stack
- Java  
- Maven  
- Selenium  
- TestNG  
- Git & GitHub  
- Eclipse IDE, IntelliJ IDE  

---

## 🔗 Project Structure Overview
```
Java-Batch-final-project/
│
├── Herokuapp/milestorefour/ 🔗 Main automation framework
│ ├── src/test/java/herokuapp/milestorefour
│ │ ├── basetest
│ │ ├── pages
│ │ ├── pagestest
│ │ ├── listeners
│ │ └── utility
│ ├── resources
│ │ └── config.properties
│ ├── pom.xml
│ └── testng.xml
│
├── four/ 🔗 Maven setup & wrapper
├── AGILE.md
├── LICENSE
└── README.md
```

---

## 🔗 Execution Instructions

### 🔗 Prerequisites
- Java JDK 11 or above  
- Maven  
- Git  

### 🔗 Run Test Suite
Navigate to the main project folder:

bash
```
cd Herokuapp/milestorefour
mvn clean test
```
🔗 Configuration
Test configuration is maintained in:
🔗 resources/config.properties

Test execution is controlled using:
🔗 testng.xml

🔗 Documentation
🔗 Agile Execution Document: AGILE.md

🔗 License: MIT License (LICENSE)

🔗 Project Status
✔ Milestone requirements completed
✔ Agile methodology followed
✔ Automation framework implemented and documented
