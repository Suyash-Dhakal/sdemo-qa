# Test Summary: SauceDemo Manual Testing

## 🔍 Overview
This document summarizes manual testing performed on [https://www.saucedemo.com](https://www.saucedemo.com), focusing on login, inventory, cart, and checkout functionalities.

## ✅ Modules Tested
- Login (valid, invalid, empty input scenarios)
- Inventory page (image verification, sorting issues)
- Cart functionality (Add/Remove bugs with `problem_user`)
- Checkout flow (input validation and success flow)

## 🧪 Test Accounts Used
- `standard_user` – for baseline testing
- `problem_user` – to explore known UI bugs
- Other test users were skipped for brevity

## 🐞 Key Issues Found (with `problem_user`)
- Product images were all the same and mismatched titles
- Sorting dropdown was unresponsive
- Add to Cart and Remove buttons did not work consistently
- Products could not be removed once added
- Input validation allowed numeric-only names during checkout

## 📌 Observations
- `standard_user` offers a smooth user journey
- `problem_user` simulates buggy behaviors for testing QA skills
- The application lacks strong frontend validation

## 📁 Files
- `saucedemo-test-cases.xlsx` – Raw test cases
- `saucedemo-test-cases.pdf` – Polished version
