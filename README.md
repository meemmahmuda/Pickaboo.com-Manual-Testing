# Pickaboo.com — Manual Testing Project

Manual QA testing documentation for [Pickaboo.com](https://www.pickaboo.com), an e-commerce platform. This repository contains the complete test plan, test scenarios, test cases, execution results, and bug reports produced during manual functional, UI, and negative testing of the website.

## 📄 File

- [View Complete Pickaboo Manual Testing Documentation](https://docs.google.com/spreadsheets/d/1i8F4Mv-lwGL_txrONE7yKIYWflarFsmBB0JGJya6O6Q/edit?usp=sharing)

## 📑 Sheets Overview

| Sheet | Description |
|---|---|
| **Test Plan** | High-level test plan overview and link to the full plan |
| **Mind Map** | Visual breakdown of test coverage areas |
| **Test Scenarios** | 18 test scenarios (TS-01 to TS-18) across major modules |
| **Pickaboo Test Case** | 126 detailed test cases (TC-1 to TC-126) with steps, test data, expected/actual results, and status |
| **Bug Report** | Individually logged bugs with reproduction steps, environment, priority, severity, and screenshots |
| **Test Case Summery Report** | Summary of pass/fail/blocked/no-run counts |
| **Test Metrics** | QA metrics derived from execution results |

## 🧠 Mind Map

<img width="848" height="1415" alt="Mind Map for Othoba com (4)" src="https://github.com/user-attachments/assets/43402361-35bb-4784-8ed7-64fff2d624fd" />

---

## 🧩 Areas Covered

| # | Area | Test Cases | Focus Areas |
|---|------|:----------:|-------------|
| 1 | Registration & Sign In | 8 | Blank fields, name/email validation, password rules, visibility toggle, duplicate email, wrong credentials |
| 2 | Home Page | 35 | Logo, header, navigation, banners, deals, product cards, cart icon, footer, responsiveness, broken links/images, browser compatibility |
| 3 | Forgot Password | 24 | Email validation, reset request/email/link, new password rules, password mismatch, XSS & SQL injection, login after reset |
| 4 | Search | 23 | Valid/partial/exact keywords, brand/model search, result display, empty/special/long input, HTML & XSS injection, Unicode/emoji |
| 5 | Category | 23 | Product listing, price sorting, filters, pagination, out of stock, responsive listing, duplicates, rapid filter clicks |
| 6 | Cart | 13 | Add/remove products, quantity change, zero/negative quantity, empty cart, totals, discounted price |
| | **Total** | **126** | |

## ▶️ How to Execute

1. Open the test case sheet and pick an area.
2. Review the preconditions and prepare the required test data.
3. Perform each test case on the application.
4. Compare the actual behavior with the expected result.
5. Mark the status as **Pass**, **Fail**.
6. For failures, log a defect with steps to reproduce, screenshots, and environment details.

---

## 🐞 Defect Reporting Template

```
Bug ID:
Title:
Area / Feature:
Severity / Priority:
Environment (Browser / Device / OS):
Preconditions:
Steps to Reproduce:
  1.
  2.
  3.
Expected Result:
Actual Result:
Attachments (Screenshot / Video):
Status:
```

---

## 🔗 User Flow Covered

```
Registration → Sign In → (Forgot Password → Reset → Login)
      → Home Page → Search / Category → Add to Cart → Cart Management
```

---

## 🐞 Testing Types Applied

- Functional Testing
- UI Testing
- Validation Testing
- Negative Testing
- Security Testing (XSS, SQL Injection)
- Compatibility Testing (Chrome, Firefox, Edge)
- Responsive Testing (Desktop, Tablet, Mobile)

## 📊 Test Summary (fill after execution)

| Area | Total | Passed | Failed | Blocked | Not Executed |
|------|:-----:|:------:|:------:|:-------:|:------------:|
| Registration & Sign In | 8 | | | | |
| Home Page | 35 | | | | |
| Forgot Password | 24 | | | | |
| Search | 23 | | | | |
| Category | 23 | | | | |
| Cart | 13 | | | | |
| **Total** | **126** | | | | |

---

## 🛠️ Test Case Format

Each test case includes:
- **Module** & **Type of Testing**
- **Feature** being tested
- **Test Case** description
- **Reproducing Steps**
- **Test Data**
- **Expected Result** vs **Actual Result**
- **Bug Screenshot/Recording** link (where applicable)
- **Final Status** (Passed / Failed)

## 👤 QA Details

- **Test Executed By:** Mahmuda Binte Sayeed
- **Test Case Developed By:** Mahmuda Binte Sayeed
- **Test Case Reviewed By:** Sabiul Islam Rashed
