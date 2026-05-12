# API Automation Testing | Postman & Newman 🚀

This repository contains an automated testing suite designed to validate API endpoints, ensuring data integrity, contract compliance, and business logic adherence.

---

### 🛠️ Technologies & Tools
* **Postman:** For collection creation and test script development.
* **Newman:** CLI tool to run collections directly in the terminal or CI/CD pipelines.
* **JavaScript:** Used for Pre-request scripts and test assertions.
* **JSON:** Standard data format for requests and responses.

---

### 📝 Key Testing Features
* **Status Code Validation:** Ensuring correct responses (200, 201, 404, etc.).
* **JSON Schema Verification:** Validating data types and mandatory fields.
* **Contract Testing:** Ensuring the API response matches the expected structure.
* **End-to-End (E2E) Workflows:** Chaining requests to simulate real-user scenarios.
* **Environment Variables:** Dynamic testing across different environments (Dev, QA, Prod).

---

### 🚀 How to Run the Tests

#### 1. Prerequisites
You need **Node.js** installed. Then, install Newman globally:
```bash
npm install -g newman
### 📝 Scenarios Tested (Registration API)
Based on the platform's authentication endpoints, I developed and executed the following test scenarios:

* **Success Cases:**
    * [cite_start]Full user registration with successful status code 201 Created. 
    * [cite_start]Automatic Role Assignment (ensuring new users default to the 'ALUNO' role). 
* **Validation & Error Handling (Negative Testing):**
    * [cite_start]**Data Integrity:** Preventing registration with duplicate CPFs. 
    * [cite_start]**Format Validation:** Blocking invalid email formats and non-standard CPF patterns (including checks for letters or symbols). 
    * [cite_start]**Business Logic:** Preventing duplicate email registration. 
    * [cite_start]**Required Fields:** Ensuring the API rejects requests with empty mandatory fields and malformed JSON. 
    * [cite_start]**Security:** Validating password strength criteria to prevent weak credentials.
