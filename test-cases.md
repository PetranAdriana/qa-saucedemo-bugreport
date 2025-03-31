# 🧪 Test Plan – SauceDemo Manual QA Project

## 1. 📌 Test Plan ID
TP-001-SAUCEDEMO

## 2. 🎯 Objective
To validate that the SauceDemo e-commerce platform functions correctly for key user flows (login, registration, product search, add to cart, send email to a friend).

## 3. 🧱 Scope
- UI Testing
- Functional Testing
- Regression Testing

## 4. ❌ Out of Scope
- Performance testing
- API testing
- Mobile testing

## 5. 🛠️ Test Types
- Smoke Testing
- Functional Testing
- Regression Testing
- UI Validation

## 6. 📋 Test Deliverables
- Test Cases document (PDF)
- Bug Report
- Screenshots of failed tests

## 7. ⏳ Entry Criteria
- Application is accessible
- Test environment is stable
- Test data is available

## 8. ✅ Exit Criteria
- All high severity test cases are passed
- All critical bugs are fixed and retested

## 9. ⚙️ Environment
- **Browser**: Chrome
- **OS**: Windows 11
- **Platform**: SauceDemo (https://www.saucedemo.com/)

 ## 9. 🧪 Test Cases

| Test Case ID | Title                  | Steps to Reproduce                                                                                                                                         | Expected Result                                      |
|--------------|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------|
| TC-001       | Verify login           | 1. Go to login page <br> 2. Enter valid credentials <br> 3. Click Login                                                                                    | User is redirected to dashboard                      |
| TC-002       | Add item to cart       | 1. Search for item <br> 2. Click "Add to cart"                                                                                                             | Item appears in the cart                             |
| TC-003       | Checkout process       | 1. Add item to cart <br> 2. Click checkout <br> 3. Fill in form <br> 4. Click "Finish"                                                                    | Order confirmation message is displayed              |
| TC-004       | Logout functionality   | 1. Login <br> 2. Click menu <br> 3. Click Logout                                                                                                           | User is redirected to login page                     |
| TC-005       | Invalid login attempt  | 1. Go to login page <br> 2. Enter invalid credentials <br> 3. Click Login                                                                                 | Error message is displayed: "Username and password do not match" |



## 10. 👤 Testers
- Adriana Petran (Junior QA Tester)


