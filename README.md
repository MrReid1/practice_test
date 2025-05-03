This repository contains automated test scripts developed using Selenium WebDriver and TestNG. The focus of this project is to test the login functionality of a web application to ensure its reliability, correctness, and behavior under different input scenarios.

Language: Java
	•	Test Framework: TestNG
	•	Browser Automation: Selenium WebDriver
	•	Build Tool: Maven


STRUCTURE
 ├── src/test/java
│   ├── tests/              # TestNG test classes
├── testng.xml              # TestNG configuration file
├── pom.xml                 # Maven configuration
└── README.md               # Project documentation


	Valid login with correct credentials
	•	Invalid login with incorrect username/password
	•	UI element presence (username, password field, login button)



 How to Run Tests

 Clone repo :  git clone https://github.com/your-username/your-repo-name.git
 Navigate to the project folder: cd your-repo-name
 Run tests using Maven: mvn test



 Notes
	•	Tests are configured to run on ChromeDriver.
	•	Update chromedriver path if not using WebDriverManager.
	•	Extend tests for multi-browser support and integration pipelines as needed.

 Future Improvements
	•	Integration with CI tools like Jenkins or GitHub Actions
	•	Enhanced reporting (Allure, Extent)
	•	Data-driven testing using Excel or JSON
	•	Cross-browser testing support
