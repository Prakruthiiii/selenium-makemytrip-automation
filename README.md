# ✈️ Travel Automation Framework (MakeMyTrip)

## 📌 Project Overview

This project is a **Selenium Automation Framework** built using **Java, TestNG, Maven, and Page Object Model (POM)**.
It automates basic user flows on the **MakeMyTrip Flights page**, such as navigating to flights and interacting with search elements.

This framework is designed as a **learning + interview-ready project** for demonstrating automation testing skills.

---

## 🛠️ Tech Stack Used

* **Java**
* **Selenium WebDriver**
* **TestNG**
* **Maven**
* **Page Object Model (POM)**
* **Git & GitHub**

---

## 📂 Project Structure

```
TravelAutomationFramework
│── src/main/java
│   ├── com.travel.base
│   │   └── BasePage.java
│   ├── com.travel.pages
│   │   └── SearchPage.java
│
│── src/test/java
│   └── com.travel.tests
│       └── FlightBookingTest.java
│
│── testng.xml
│── pom.xml
│── .gitignore
│── README.md
```

---

## 🚀 Features Implemented

* Launch MakeMyTrip website
* Navigate to **Flights** section
* Handles dynamic elements using **Explicit Waits**
* Proper driver setup and teardown
* Test execution using **TestNG**

---

## ▶️ How to Run the Project

### Prerequisites

* Java JDK 17 or above
* Maven installed
* Chrome browser
* ChromeDriver (compatible with Chrome version)

### Steps to Execute

1. Clone the repository:

```bash
git clone <your-repo-url>
```

2. Open the project in **Eclipse / IntelliJ**

3. Update Maven dependencies:

```bash
mvn clean install
```

4. Run the test:

* Right-click `testng.xml` → **Run as TestNG Suite**

---

## 🧪 Test Case Example

* `testFlightSearch()`

  * Opens MakeMyTrip
  * Navigates to Flights page
  * Verifies successful interaction

---

## ⚠️ Challenges Faced

* Dynamic popups blocking elements
* ElementClickInterceptedException
* Handling waits and page load timing

These were resolved using **Explicit Waits** and better element handling.

---

## 📌 Future Enhancements

* Add Extent Reports
* Data-driven testing (Excel)
* Screenshot capture on failure
* CI/CD integration

---

## 👩‍💻 Author

**Prakruthi H**

* Computer Science Graduate
* Selenium Automation Learner

---

⭐ If you like this project, give it a star on GitHub!
