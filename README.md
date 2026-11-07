# QA Test Documentation

Manual testing portfolio: test case design, test execution, and bug reporting across web and mobile applications.

**Author:** Mona Abouelnaga — Software QA Engineer

> 📄 Each project includes a **PDF** that opens directly in the browser — click it to view.

---

## Projects

| Project | Platform | Deliverables | Highlights |
|---|---|---|---|
| [Disputes Module](./Disputes-Module/) | Web (freelance marketplace) | Test cases, bug report, Figma vs live comparison | 31 test cases executed, **11 bugs reported** |
| [SyncShop](./SyncShop/) | Web (multi-merchant e-commerce) | Test cases + summary dashboard | 50 test cases across 8 modules |
| [Yalla Kora](./Yalla-Kora/) | Mobile app (sports) | Test cases | Smoke suite for the Favorite Teams feature |

---

### 🐞 Disputes Module — QA Report
Exploratory and functional testing of a live freelance marketplace's disputes module, compared against the Figma design.

- **31 test cases:** 7 Pass · 10 Fail · 14 Blocked (blockers documented with what is needed to continue)
- **11 bugs:** 3 High · 2 Medium · 6 Low — each with steps to reproduce, expected vs actual, severity, and a suggested fix
- **Coverage:** access control, navigation, empty states, localization (EN/AR, RTL), light/dark theme, responsive (desktop & mobile), error handling
- **Figma vs live site** comparison sheet

> The platform name, URLs and test account were anonymized, and details of one security finding were withheld from this public version.

### 🛒 SyncShop — Test Cases
Test case design for a multi-merchant e-commerce platform.

- **50 test cases** — 29 positive, 21 negative
- **Modules:** Cart, Coupons, Shipping, Order Summary, Multi-Merchant Isolation, User Roles & Permissions, Order Lifecycle, Payment
- **Techniques:** boundary value analysis (e.g. cart limit of exactly 20 vs 21 items), equivalence partitioning (coupon minimums, stock levels), business-rule validation
- **Status:** core Cart cases executed (Pass); remaining cases designed and ready for execution
- Summary sheet with live counts by status, module, and priority

### ⚽ Yalla Kora — Test Cases
Mobile test cases for the Favorite Teams feature of a sports app (Arabic UI).

- Add, view, edit and remove favorite teams
- Tagged as a **Smoke** suite with priority and scenario type

---

## Related Repositories
- **UI Automation (Playwright):** [ecommerce-ui-automation](https://github.com/Monaammar/ecommerce-ui-automation)
- **API Testing (Postman):** [weather-api-tests](https://github.com/Monaammar/weather-api-tests)
