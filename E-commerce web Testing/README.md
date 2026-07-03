# 🧪 SauceDemo Manual QA Testing Project

A complete **manual QA testing portfolio project** performed on [SauceDemo](https://www.saucedemo.com/), a demo e-commerce web application. This project demonstrates end-to-end manual testing skills — test planning, test case design, exploratory/negative testing, and defect reporting — using industry-standard documentation.

> 📌 Built as a portfolio project to demonstrate manual testing skills for QA Engineer / SDET roles.

---

## 📂 Project Contents

| File | Description |
|---|---|
| `Test_Plan_SauceDemo.docx` | Formal test plan — scope, strategy, environment, entry/exit criteria, risks |
| `Test_Cases_SauceDemo.xlsx` | 60+ manual test cases across 6 modules (Login, Inventory, Sorting, Cart, Checkout, Logout) |
| `Bug_Report_SauceDemo.xlsx` | 8 documented defects with severity, priority, and repro steps |

---

## 🎯 Application Under Test

**SauceDemo** ([saucedemo.com](https://www.saucedemo.com/)) is a simulated e-commerce store built for QA practice. It ships with several special test accounts that intentionally trigger different bugs — ideal for practicing exploratory and negative testing.

| Username | Password | Purpose |
|---|---|---|
| `standard_user` | `secret_sauce` | Baseline/happy-path user |
| `locked_out_user` | `secret_sauce` | Verifies login lockout handling |
| `problem_user` | `secret_sauce` | Seeded UI/functional bugs (broken images, sort, add-to-cart) |
| `performance_glitch_user` | `secret_sauce` | Seeded performance delay |
| `error_user` | `secret_sauce` | Seeded cart interaction errors |
| `visual_user` | `secret_sauce` | Seeded visual/layout bugs |

---

## ✅ Testing Scope

- Login & Authentication (positive, negative, boundary, security)
- Product Inventory listing & Add to Cart
- Sorting & Filtering
- Shopping Cart management
- Checkout flow (info form → overview → order confirmation)
- Logout & session handling

**Techniques used:** Equivalence Partitioning, Boundary Value Analysis, Positive/Negative Testing, Exploratory Testing, UI Testing, Regression Testing.

---

## 🐞 Sample Defects Found

| ID | Title | Severity |
|---|---|---|
| BUG_001 | Duplicate/incorrect product images for `problem_user` | Major |
| BUG_002 | 'Add to Cart' unresponsive for certain products (`problem_user`) | Critical |
| BUG_003 | UI layout misaligned for `visual_user` | Minor |
| BUG_005 | Significant page load delay for `performance_glitch_user` | Medium |
| BUG_006 | Sort order doesn't update for `problem_user` | Major |
| BUG_007 | 'Remove' button unresponsive on Cart page for `error_user` | Major |

Full details, repro steps, and severity/priority definitions are in `Bug_Report_SauceDemo.xlsx`.

---

## 🛠️ Tools & Skills Demonstrated

- Manual black-box testing techniques
- Test plan authoring (ISTQB-aligned structure)
- Test case design (Excel, filterable, with Pass/Fail tracking)
- Defect/bug reporting (Severity vs Priority)
- Exploratory testing using seeded-bug test accounts
- Chrome DevTools (console error verification)

---

## 🚀 How to Use This Project

1. Clone this repository.
2. Open `Test_Plan_SauceDemo.docx` to understand scope and strategy.
3. Open `Test_Cases_SauceDemo.xlsx` to review/execute test cases against [saucedemo.com](https://www.saucedemo.com/).
4. Cross-reference failed test cases with `Bug_Report_SauceDemo.xlsx` for defect details.

---

## 👤 About Me

QA fresher building hands-on manual testing experience. Open to **QA / Manual Tester** opportunities.

📧 [dhavaltrivedi122002@gmail.com] | 🔗 [LinkedIn]www.linkedin.com/in/dhaval-trivedi-37b923217 | 💻 [GitHub]https://github.com/dhavaltrivedi122002-source