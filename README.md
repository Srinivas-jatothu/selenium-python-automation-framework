# 🚀 Selenium Python Automation Framework

A scalable and maintainable **test automation framework** built using **Selenium WebDriver, Python, and PyTest** to automate end-to-end testing of a web-based e-commerce application.

This project follows industry best practices like **Page Object Model (POM)**, **data-driven testing**, and **modular design** to ensure clean, reusable, and efficient test automation.

---

## 📌 Overview

This framework is designed to automate core functionalities of an e-commerce platform such as:

- User Login  
- User Registration  
- Product Search  

It combines multiple automation concepts into a **hybrid framework** that is easy to extend and maintain.

---

## ✨ Features

- ✅ Page Object Model (POM) design pattern  
- ✅ Data-driven testing using Excel  
- ✅ PyTest framework with fixtures  
- ✅ Multi-browser support (Chrome, Firefox, Edge)  
- ✅ Centralized configuration management  
- ✅ Allure reporting with screenshot capture  
- ✅ Reusable utility modules  
- ✅ Clean and modular project structure  

---

## 🛠 Tech Stack

- **Language:** Python  
- **Automation Tool:** Selenium WebDriver  
- **Test Framework:** PyTest  
- **Reporting:** Allure  
- **Data Handling:** OpenPyXL  
- **Driver Management:** WebDriver Manager  

---

## 📁 Project Structure

```
selenium-python-automation-framework/
│
├── pages/              # Page Object classes
├── tests/              # Test cases
├── utilities/          # Helper utilities
├── configurations/     # Config files
├── ExcelFiles/         # Test data
│
├── requirements.txt    # Dependencies
├── .gitignore          # Ignored files
└── README.md           # Documentation
```


---

## 🧠 Framework Architecture

### 🔹 Page Object Model (POM)

Each webpage is represented as a class containing:
- Locators  
- Actions (methods)  

**Benefits:**
- Improves maintainability  
- Reduces code duplication  
- Makes test cases more readable  

---

### 🔹 Data-Driven Testing (DDT)

Test data is stored externally in Excel files and used in test execution.

**Benefits:**
- Run tests with multiple datasets  
- Easy to update test inputs  
- Improves test coverage  

---

### 🔹 PyTest Fixtures

Used for:
- Browser setup and teardown  
- Test configuration  
- Reusable test setup  

---

## ⚙️ Setup & Installation

### 1. Clone the repository

```
git clone https://github.com/Srinivas-jatothu/selenium-python-automation-framework.git
cd selenium-python-automation-framework
```

### 2. Create virtual environment

```
python -m venv venv
venv\Scripts\activate   # For Windows
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Running Tests

Run all tests:

```
pytest -v
```

Run specific test:

```
pytest tests/test_Login.py -v
```

---

## 📊 Test Reporting (Allure)

Generate report:

```
pytest --alluredir=Reports/
```

View report:

```
allure serve Reports/
```


---

## 🧪 Test Scenarios Covered

### 🔐 Login
- Valid login  
- Invalid login  
- Empty credentials  

### 📝 Registration
- Successful registration  
- Duplicate email validation  

### 🔍 Search
- Valid product search  
- Invalid search  
- No results scenario  

---

## ✅ Best Practices Implemented

- ✔ Page Object Model (POM)  
- ✔ Separation of concerns  
- ✔ External configuration management  
- ✔ Reusable components  
- ✔ Modular design  
- ✔ Clean folder structure  

---

## 🚧 Future Enhancements

- Add CI/CD using GitHub Actions  
- Add API testing  
- Parallel test execution  
- Docker integration  
- Logging framework  

---

## 👨‍💻 Author

**Srinivas Jatothu**

- GitHub: https://github.com/Srinivas-jatothu  

---

## ⭐ Final Note

This project demonstrates real-world **QA automation practices** and serves as a strong foundation for building scalable automation frameworks in enterprise environments.