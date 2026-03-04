🛒 E-Commerce Website Automation Testing (Selenium + JUnit)

This project contains automated test scripts for an E-Commerce website built using Java, Selenium WebDriver, and JUnit 5.

The automation tests validate different functionalities such as login, signup, product search, add to cart, checkout, contact form submission, and more.

The testing is performed on the demo website:

🔗 https://automationexercise.com

🚀 Technologies Used

Java

Selenium WebDriver

JUnit 5

ChromeDriver

Eclipse IDE

📂 Project Structure
ECommerceWebsite
│
├── addtocart.java
├── cart.java
├── contactus.java
├── econnerce.java
├── logginpage.java
├── logout.java
├── placeorder.java
├── registsamemail.java
├── removeprocart.java
├── scrollsubscription.java
├── testcasebtn.java
├── verifyallproduct.java
├── viewPro.java
└── wronginfo.java

Each class represents a separate automated test scenario for the E-Commerce website.

✅ Automated Test Scenarios
1️⃣ User Login Tests

File: logginpage.java

Tests:

Login with valid credentials

Verify successful login

Delete account after login

2️⃣ Login Negative Test Cases

File: wronginfo.java

Tests:

Wrong email & wrong password

Correct email & wrong password

Wrong email & correct password

Blank email field

Blank password field

Expected Result

Your email or password is incorrect!
3️⃣ User Registration

File: econnerce.java

Automates the complete signup process, including:

Name

Email

Password

Date of Birth

Address Information

Country Selection

Mobile Number

Expected Result

Account Created!
4️⃣ Register with Existing Email

File: registsamemail.java

Tests signup using an already registered email address.

Expected Result

Email Address already exist!
5️⃣ Logout Functionality

File: logout.java

Tests:

Login with valid credentials

Click Logout

Verify successful logout

6️⃣ Product Search

File: verifyallproduct.java

Tests:

Navigate to the Products page

Search for a product

Example product searched:

Blue Top
7️⃣ View Product Details

File: viewPro.java

Tests:

Open the Products page

Scroll down the page

Click View Product

8️⃣ Add Product to Cart

File: addtocart.java

Tests:

Hover over a product

Click Add to Cart

Uses the Actions class for mouse hover functionality.

9️⃣ Remove Product from Cart / Add Product Flow

File: removeprocart.java

Tests:

Login to the application

Add a product to the cart

Navigate to View Cart

Uses:

WebDriverWait

ExpectedConditions

JavaScriptExecutor

🔟 Cart Page Subscription

File: cart.java

Tests:

Open the Cart page

Subscribe using an email address

1️⃣1️⃣ Footer Subscription

File: scrollsubscription.java

Tests:

Scroll to the subscription section

Enter email

Subscribe

1️⃣2️⃣ Contact Us Form

File: contactus.java

Tests:

Navigate to Contact Us

Fill out the form

Upload a file

Submit the form

Expected Result

Success! Your details have been submitted successfully.
1️⃣3️⃣ Test Cases Page Verification

File: testcasebtn.java

Tests:

Navigate to the Test Cases page

Verify the page heading

1️⃣4️⃣ Place Order

File: placeorder.java

Tests:

Login to the application

View product details

Add product to cart

View cart

Proceed to checkout

Place order

Enter payment details

Example Payment Data Used:

Card Name : archit
Card Number : 12345
CVC : 123
Expiry : 09 / 2026

Expected Result

Order Placed Successfully
⚙️ Setup & Installation
1️⃣ Clone the Repository
git clone https://github.com/yourusername/ECommerce-Automation-Testing.git
2️⃣ Open the Project

Open the project in Eclipse IDE.

3️⃣ Install Required Dependencies

Ensure the following dependencies are added:

Selenium WebDriver

JUnit 5

ChromeDriver

4️⃣ Run the Tests

Run the test classes using:

Run As → JUnit Test
🧪 Testing Concepts Covered

This project demonstrates:

Functional Testing

UI Testing

Negative Testing

Automation Testing

Web Element Handling

Alert Handling

File Upload Testing

Page Scrolling

Wait Mechanisms (Implicit & Explicit Waits)

JavaScript Executor usage

📌 Features

✔ Automated UI Testing
✔ Multiple Test Scenarios
✔ Selenium WebDriver Implementation
✔ JUnit Test Structure
✔ Page Interaction Automation

👨‍💻 Author

Archit Singh

Automation Tester | Selenium | Java | API Testing

Skills:

Manual Testing

Selenium WebDriver

Postman

SOAP UI

Bug Reporting
