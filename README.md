# 🧪 SauceDemo Automation – Selenium Java

This project automates a full user checkout journey on [SauceDemo](https://www.saucedemo.com/) using **Java + Selenium WebDriver**.  
It includes login, cart actions, form filling, and final order submission – all in an incognito Chrome session.

---

## 🔧 Tools & Technologies

| Tool/Library                | Purpose                                 |
|----------------------------|-----------------------------------------|
| **Java**                   | Main programming language               |
| **Selenium WebDriver**     | Browser automation                      |
| **WebDriverManager**       | Automatically manages ChromeDriver      |
| **ChromeDriver**           | Used to launch Google Chrome            |
| **IntelliJ IDEA** *(opt.)* | Recommended IDE for Java development    |

---

## ▶️ How to Run

1. **Install Prerequisites:**
   - Java JDK 8 or higher
   - Maven (if not bundled with IDE)
   - Chrome browser

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/sauce-selenium-automation.git
   cd sauce-selenium-automation

---
## Assumptions

### In Checkout Form:
- First name field boundaries: 1 to 50 characters.
- Zip code field expects only numbers.

### User Interface:
- Login button should be disabled when fields are empty.

## Documentation

All related documents are included in the `Build` folder and contain the following:

- **Test Plan**  
  A brief test plan with objectives and scope → `Test plan.pdf`

- **Test Cases**  
  Well-structured test cases → `sause demo website Test Cases.pdf` / `sause demo website Test Cases.xlsx`

- **Bug Reports**  
  A bug report template and examples → `Bug ReportS.pdf`
