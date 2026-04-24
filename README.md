# 🚆 TrainConsistManagementApp

## 📌 Overview

**TrainConsistManagementApp** is a Java-based application that simulates real-world **train consist management systems**. It enables operations on bogies (train coaches) such as adding, searching, grouping, and validating data.

The project follows a **use-case driven development approach (UC1–UC20)** and demonstrates:

* Git branching strategy
* Unit testing with JUnit
* Exception handling
* Modular programming

---

## 🚀 Features

### 🔹 Core Functionalities

* Add and manage bogies (train coaches)
* Search bogies using **Linear Search**
* Organize and group train consist
* Validate input data
* Handle invalid operations using exceptions

### 🔹 Advanced Functionalities

* Binary Search optimization (UC19)
* Exception handling in search (UC20)
* Modular design using multiple use cases
* Unit testing with JUnit

---

## 🧱 Project Structure

```
TrainConsistManagementApp/
│── App/
│   └── src/
│       ├── main/
│       │   ├── UC1.java
│       │   ├── UC2.java
│       │   ├── ...
│       │   ├── UC20.java
│       │   └── TrainConsistManagementApp.java
│       │
│       └── test/
│           ├── UC1Test.java
│           ├── UC2Test.java
│           ├── ...
│           └── UC20Test.java
│
│── README.md
```

---

## ⚙️ Technologies Used

* ☕ **Java (JDK 8+)**
* 🧪 **JUnit 5** (`org.junit.jupiter:junit-jupiter:5.10.0`)
* 🧠 Object-Oriented Programming (OOP)
* 📦 Java Collections Framework
* 🔧 Git & GitHub (Branching Strategy)

---

## 🧪 Testing Setup

JUnit is used to test each use case.

### 🔹 Add JUnit Dependency (IntelliJ)

1. Go to:
   `File → Project Structure → Libraries`
2. Click ➕ → **From Maven**
3. Add:

```
org.junit.jupiter:junit-jupiter:5.10.0
```

---

## 🌿 Git Workflow (Lab Standard)

### 🔹 Branch Structure

```
main (protected)
  ↑
dev (integration branch)
  ↑
feature/UCx (development)
```

---

### 🔹 Workflow Steps

```bash
# Create dev branch
git checkout -b dev
git push origin dev

# Create feature branch
git checkout -b feature/UC20-ExceptionHandlingInSearch

# Add & Commit changes
git add .
git commit -m "Added UC20 Exception Handling"

# Push changes
git push origin feature/UC20-ExceptionHandlingInSearch
```

### 🔹 Pull Request Rules

* ✅ Always merge: **feature → dev**
* ❌ Never merge: **dev → main**

---

## 🧠 Key Concepts Implemented

* Linear Search
* Binary Search
* Exception Handling
* Unit Testing (JUnit)
* Modular Programming
* Git Branching Strategy

---

## 📊 Example (UC20 - Exception Handling)

```java
if (bogieIds.length == 0) {
    throw new IllegalStateException("No bogies available for search");
}
```

### ✔ Demonstrates:

* Runtime validation
* Safe search operations
* Proper exception handling

---

## 📌 Use Cases Covered

* **UC1** – Basic setup
* **UC8** – Train consist logic + testing
* **UC9–UC19** – Searching, grouping, optimization
* **UC20** – Exception handling in search

---

## ▶️ How to Run

### 1️⃣ Clone Repository

```bash
git clone https://github.com/devcrazy2812/TrainConsistManagementApp.git
cd TrainConsistManagementApp
```

### 2️⃣ Compile

```bash
javac *.java
```

### 3️⃣ Run

```bash
java Main.UC20
```

---

## 🧠 Learning Outcomes

* Real-world DSA implementation
* Writing testable Java applications
* Using JUnit for testing
* Applying Git workflow in projects
* Handling edge cases and exceptions

---

## 📌 Real-World Applications

* Railway coach management systems
* Logistics and transport optimization
* Backend service logic design
* Search-based systems with validation

---

## 🙌 Author

**Abhay Goyal**

---

## ⭐ Contribution

Feel free to:

* Fork the repository
* Improve code logic
* Add new use cases
* Enhance test coverage

---

## 📜 License

This project is for educational purposes only.
