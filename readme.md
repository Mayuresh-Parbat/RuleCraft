# RuleCraft 🚀

## Dynamic Rule Engine Platform built with Java

RuleCraft is a configurable and extensible Rule Engine designed to execute dynamic business rules efficiently. The platform allows users to create, manage, and evaluate rules dynamically without changing application code.

This project focuses on backend engineering concepts using Java, including rule parsing, condition evaluation, execution pipelines, design patterns, and scalable architecture.

---

## 📌 Overview

**RuleCraft** is a powerful and extensible **Rule Engine Platform** built using Java and Spring Boot that enables dynamic creation, management, and execution of business rules without modifying application code.

The platform is designed to simulate how enterprise-grade rule engines operate internally by focusing on scalable backend architecture, modular design, rule parsing, execution pipelines, and condition evaluation mechanisms.

This project demonstrates advanced backend engineering concepts including clean architecture, design patterns, REST API development, dynamic logic execution, and scalable system design.

---

# ✨ Key Features

✅ Dynamic Rule Creation & Management  
✅ Real-Time Rule Evaluation  
✅ Nested Logical Conditions (AND / OR)  
✅ Priority-Based Rule Execution  
✅ Modular Rule Processing Pipeline  
✅ Rule Validation & Error Handling  
✅ RESTful API Architecture  
✅ Extensible & Scalable Design  
✅ Exception Handling & Centralized Logging  
✅ Configurable Rule Definitions  

---

# 🏗️ System Architecture

```text
                ┌────────────────────┐
                │   Client / UI      │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ REST Controllers   │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │  Service Layer     │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Rule Engine Core   │
                └─────────┬──────────┘
                          │
                          ▼
                ┌────────────────────┐
                │ Database Layer     │
                └────────────────────┘
```

---

# ⚙️ Tech Stack

## 🔹 Backend
- Java
- Spring Boot
- Spring Data JPA
- Maven

## 🔹 Database
- MySQL

## 🔹 Frontend (Optional)
- React.js

---

# 📂 Project Structure

```text
rulecraft/
│
├── controller/        → REST API Controllers
├── service/           → Business Logic Layer
├── model/             → Entity & DTO Classes
├── repository/        → Database Operations
├── engine/            → Core Rule Evaluation Engine
├── exception/         → Custom Exception Handling
├── config/            → Application Configurations
├── resources/         → Properties & Static Resources
└── util/              → Utility Classes
```

---

# 🔥 Core Backend Concepts Implemented

## ✅ Object-Oriented Programming
- Encapsulation
- Abstraction
- Inheritance
- Polymorphism

## ✅ Design Patterns
- Strategy Pattern
- Factory Pattern
- Chain of Responsibility
- Builder Pattern

## ✅ Backend Engineering
- REST API Development
- Dynamic Rule Parsing
- Condition Evaluation
- Validation Pipelines
- Layered Architecture
- Exception Handling
- Logging Mechanisms

## ✅ Database Integration
- Spring Data JPA
- Hibernate ORM
- MySQL Integration

---

# 🚀 Sample Rule JSON

```json
{
  "ruleName": "Loan Eligibility",
  "priority": 1,
  "conditions": [
    {
      "field": "salary",
      "operator": ">",
      "value": 50000
    },
    {
      "field": "creditScore",
      "operator": ">=",
      "value": 700
    }
  ],
  "logic": "AND"
}
```

---

# 📡 REST API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/rules` | Create New Rule |
| GET | `/rules` | Fetch All Rules |
| GET | `/rules/{id}` | Fetch Rule By ID |
| PUT | `/rules/{id}` | Update Existing Rule |
| DELETE | `/rules/{id}` | Delete Rule |
| POST | `/rules/evaluate` | Evaluate Rule Logic |

---

# 💻 Getting Started

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/rulecraft.git
```

---

## 2️⃣ Navigate to Project

```bash
cd rulecraft
```

---

## 3️⃣ Configure Database

Update your `application.properties` file:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/rulecraft
spring.datasource.username=root
spring.datasource.password=yourpassword
```

---

## 4️⃣ Run Application

```bash
mvn spring-boot:run
```

---

# 🧠 How Rule Evaluation Works

```text
Input Request
      ↓
Rule Parser
      ↓
Condition Validator
      ↓
Execution Engine
      ↓
Priority Resolver
      ↓
Final Evaluation Result
```

---

# 🚀 Future Enhancements

- Visual Drag-and-Drop Rule Builder
- Rule Versioning System
- Workflow Engine Integration
- Real-Time Event Streaming
- Distributed Rule Processing
- Rule Analytics Dashboard
- Audit Logs & Monitoring
- Docker & Kubernetes Deployment
- Authentication & Authorization
- AI-Assisted Rule Suggestions

---

# 📈 Learning Outcomes

This project helps strengthen practical knowledge in:

- Enterprise Backend Development
- Clean Architecture
- Scalable System Design
- Java Design Patterns
- Rule Processing Systems
- API Engineering
- Database Management
- Production-Level Backend Structuring
- 
---

# 👨‍💻 Author

**Mayuresh Parbat**
