# 🏦 Banking API Testing using Postman

## 📌 Project Overview
This repository contains a complete API testing project using Postman for the Open Bank Project sandbox. The goal is to demonstrate REST API testing skills with positive, negative, security, and chained test scenarios.

## 🚀 Features Tested
- GET Banks (dynamic data extraction)
- GET Accounts (using dynamic bankId)
- Negative tests (invalid version, unauthorized write)
- POST payload validation using echo service
- PUT / PATCH / DELETE security validation
- Automated assertions with JavaScript

## 🧩 Tools Used
- Postman
- Postman Environments
- JavaScript test scripts

## 🗂 Files in This Repository
- `*.json` – Postman collection & environment
- `README.md` – Project documentation

## 🔄 How to Use
1. Download the collection & environment JSONs
2. Open Postman
3. Import both files
4. Select the `OBP-Sandbox` environment
5. Run individual requests or the entire collection

## 📈 Testing Approach
- **Functional Testing:** Validate correct API responses
- **Negative Testing:** Invalid requests and error handling
- **Security Testing:** Unauthorized attempts blocked
- **API Chaining:** Extract values and reuse in subsequent calls

## ⭐ Skills Demonstrated
- REST API testing
- Environment management
- Dynamic data handling
- Test automation with Postman
