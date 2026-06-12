📌 About This Project
This is an end-to-end test automation framework built for the SauceDemo e-commerce website. It automatically tests the core user journey — Login → Browse Products → Add/Remove from Cart → Checkout → Order Confirmation — just like a real user would, but without manual clicking.
The framework is built using:

Java – core programming language
Selenium WebDriver – to control the browser and interact with web elements
TestNG – to organize, run, and prioritize test cases, and to verify expected results
Maven – to manage project dependencies and run tests from the command line
Page Object Model (POM) – a clean design pattern where each web page has its own class, making the code easier to maintain and reuse
ExtentReports – to generate detailed, easy-to-read HTML test reports with pass/fail status and failure screenshots

What it tests

✅ Valid and invalid login scenarios (correct credentials, wrong password, empty fields, locked-out user)
✅ Logging out
✅ Searching and viewing products
✅ Adding and removing items from the cart
✅ Completing checkout and verifying order confirmation

Why this project matters
This project simulates how a QA Engineer ensures a real e-commerce application works correctly across its most critical flows. It also reflects real industry practices — config-driven testing (no hardcoded data), reusable page classes, and professional reporting — making it easy to scale, maintain, and run repeatedly (for example, before every new release).
<img width="1738" height="947" alt="console" src="https://github.com/user-attachments/assets/39757f90-0d38-45d8-a671-d64b57f9af91" />
<img width="1918" height="1018" alt="report" src="https://github.com/user-attachments/assets/3874c4dc-709b-4a99-9a55-b0758ed9574b" />
<img width="1808" height="1052" alt="saucedemo_test" src="https://github.com/user-attachments/assets/1fccf215-6102-4780-883a-773720c46090" />
<img width="473" height="785" alt="structure" src="https://github.com/user-attachments/assets/46c8fc07-1d26-4f4e-9faa-bbdb91029a96" />
<img width="722" height="763" alt="TestNG" src="https://github.com/user-attachments/assets/4b1394b0-37d8-40f2-a342-48fc4b9783fb" />
