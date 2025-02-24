# 📝 Swag Labs Login Testing

## 📌 Overview  
This repository contains **manual test cases** for testing the **login functionality** of Swag Labs (`https://www.saucedemo.com/`). The test cases validate user authentication by checking various combinations of **valid and invalid credentials**.

---

## 📂 Test Cases  
The following test cases are covered in this repository:

| TC#ID  | Test Scenario | Test Data | Expected Result | Status |
|--------|--------------|----------|----------------|--------|
| TC_SwagLabs_001 | Valid username & valid password | ✅ Valid Credentials | Login should be successful | ✅ PASS |
| TC_SwagLabs_002 | Valid username & invalid password | ❌ Incorrect Password | Error message displayed | ✅ PASS |
| TC_SwagLabs_003 | Invalid username & valid password | ❌ Incorrect Username | Error message displayed | ✅ PASS |
| TC_SwagLabs_004 | Invalid username & invalid password | ❌ Incorrect Credentials | Error message displayed | ✅ PASS |

---

## 🔍 **How to Use This Repository**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/SwagLabs-Login-Testing.git
