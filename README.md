# 🛡️ API Security Risk Analysis

## 📌 Project Overview

This project focuses on analyzing security risks in public/demo APIs using tools like Postman, Browser DevTools, and manual security testing techniques. The objective is to identify common API vulnerabilities, understand their impact, and suggest remediation methods following secure API development practices.

The project demonstrates practical knowledge of:
- API security testing
- Authentication & authorization assessment
- Risk identification
- Security documentation
- SaaS/API security fundamentals

---

# 🎯 Objectives

- Identify insecure API endpoints
- Analyze authentication and authorization mechanisms
- Detect missing rate-limiting protections
- Test input validation weaknesses
- Identify sensitive data exposure risks
- Document vulnerabilities professionally
- Provide remediation recommendations

---

# 🧰 Tools Used

| Tool | Purpose |
|------|----------|
| Postman | API request testing |
| Browser DevTools | Network/API inspection |
| VS Code | Documentation |
| GitHub | Project hosting |
| Public Demo APIs | Safe testing environment |

---

# 🌐 APIs Used for Testing

## Fake Store API
https://fakestoreapi.com/

## ReqRes API
https://reqres.in/

## JSONPlaceholder
https://jsonplaceholder.typicode.com/

---

# 🔍 Security Areas Tested

- Authentication Security
- Authorization & Access Control
- Input Validation
- Rate Limiting
- Sensitive Data Exposure
- HTTP Security Headers
- Error Handling & Information Disclosure

---

# ⚠️ Vulnerabilities Analyzed

## 1. Broken Authentication
- Weak or exposed authentication mechanisms
- Token handling analysis

## 2. Broken Authorization (BOLA)
- Accessing unauthorized resources by changing object IDs

## 3. Missing Rate Limiting
- Unlimited API requests allowed

## 4. Sensitive Data Exposure
- Exposure of tokens, credentials, or internal data

## 5. Improper Input Validation
- Malicious input handling issues

## 6. Missing Security Headers
- Lack of essential HTTP security protections

---

# 🧪 Example API Requests

## GET Request

```http
GET https://fakestoreapi.com/products
