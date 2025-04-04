# 🐾 PetStore RestAssured Automation

This project provides automated API testing for the [Swagger PetStore API](https://petstore.swagger.io/) using **RestAssured** with **Java**, **TestNG**, **ExtentReports**, and **Log4j**.

## 📌 Tech Stack

- **Java**
- **RestAssured** – for API automation
- **TestNG** – for test execution and assertions
- **ExtentReports** – for rich HTML reporting
- **Log4j** – for logging and debugging
- **Maven** – for build and dependency management

---


## 🚀 How to Run the Tests

### 🧰 Prerequisites

- Java 8 or higher
- Maven
- IDE (e.g., IntelliJ IDEA or Eclipse)

### ✅ Steps

1. **Clone the repo**  
   ```bash
   git clone https://github.com/rishikeshyadav735/PetStoreRestAssuredAutomation.git
   cd PetStoreRestAssuredAutomation


Running Tests
To execute the tests, use the following command:
mvn test

Alternatively, run tests via TestNG or using the Cucumber runner class in your IDE.

📊 Reporting
After execution, a detailed Extent Report is generated at:
test-output/ExtentReport.html

📓 Features Covered
✅ Add a new pet

✅ Get pet by ID

✅ Update pet details

✅ Delete pet

✅ Negative testing and validations

🛠️ Logging
All logs are managed using Log4j and saved in:
logs/application.log

📬 API Reference
This project is based on Swagger PetStore OpenAPI Spec.

🤝 Contributions
Feel free to fork and raise a pull request. Suggestions and improvements are welcome!
