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
## 🔍Assumptions

### In Checkout Form:
- First name field boundaries: 1 to 50 characters.
- Zip code field expects only numbers.

### User Interface:
- Login button should be disabled when fields are empty.

## 📂Documentation

All related documents are included in the `Build` folder and contain the following:

- **Test Plan**  
  A brief test plan with objectives and scope → `Test plan.pdf`

- **Test Cases**  
  Well-structured test cases → `sause demo website Test Cases.pdf` / `sause demo website Test Cases.xlsx`

- **Bug Reports**  
  A bug report template and examples → `Bug ReportS.pdf`

---  
## 🎥 Demo Video

Watch the Selenium automation solution in action here:  
🔗 [Demo Video on Google Drive](https://drive.google.com/file/d/1cfytA7C5LZ65zbwg-K0GLzbj2eTTJ2mL/view?usp=sharing)

## ✅ Steps of the Solution

1️⃣ Login with valid credentials  
2️⃣ Click on **Login**  
3️⃣ Add a product to the cart 🛒  
4️⃣ Check the cart contents 🧾  
5️⃣ Remove the product from the cart ❌  
6️⃣ Go back to the main page 🔙  
7️⃣ Add a product to the cart again ➕  
8️⃣ Proceed to **Checkout** 🧾  
9️⃣ Fill the checkout form with:
   - First name
   - Last name
   - Zip code 📮  
🔟 Order is placed successfully 🎉

