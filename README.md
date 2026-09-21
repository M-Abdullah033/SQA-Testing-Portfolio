# SQA Testing Portfolio

A practical **Software Quality Assurance (SQA) testing portfolio** demonstrating hands-on testing across multiple software environments, including a Unity-based game, AI chat applications, a government portal, and a public REST API.

The portfolio focuses on **test case design, test execution, functional testing, smoke testing, negative testing, exploratory testing, regression testing, retesting, API testing, input validation, and bug reporting**.

---

## Portfolio Contents

### 1. SQA Testing Portfolio

`SQA-Testing-Portfolio.pdf`

The main portfolio presents selected testing work from six testing scenarios across five different environments.

It includes:

- Test scenarios and test cases
- Test execution results
- Expected vs. actual results
- Bug reports
- Steps to reproduce
- Retesting information where applicable
- Testing limitations and observations

The PDF presents a **selected portion of the overall testing work** where the complete testing material would make the document unnecessarily large.

### 2. Restful-Booker API Testing

`Restful-Booker API Testing.postman_collection.json`

This Postman collection contains the broader testing work performed for **TS-06: Restful-Booker API Testing**.

The collection covers:

- GET, POST, PUT, PATCH, and DELETE operations
- Positive and negative testing
- CRUD testing
- Input validation
- Missing fields
- Invalid fields and values
- Invalid data formats
- Authentication testing
- Non-existent IDs
- Update and deletion behavior
- HTTP response status codes
- Response data validation
- Bug identification
- Postman test scripts

The collection contains additional TS-06 testing work that was not included in the PDF because the complete API testing material would make the portfolio unnecessarily large.

---

## Testing Environments

The portfolio covers six testing scenarios across five environments:

- **Unity game**, built collaboratively as part of a university project. I contributed to development and independently performed testing, bug identification, and bug fixes for this portfolio.
- **Gemini**
- **DeepSeek**
- **Government job portal**
- **Restful-Booker public REST API**

Gemini and DeepSeek are separate testing scenarios while belonging to the broader category of AI chat applications.

---

## Testing Areas

The practical testing work includes:

- Functional Testing
- Smoke Testing
- Negative Testing
- Exploratory Testing
- Regression Testing
- Retesting
- UI Testing
- Input Validation
- API Testing
- Authentication Testing
- CRUD Testing
- Boundary and invalid-input testing
- Bug Reporting
- Expected vs. Actual Result Analysis

---

## Bug Reporting

Identified bugs were documented using a structured bug-reporting approach, including relevant information such as:

- Bug title
- Environment
- Preconditions
- Steps to reproduce
- Expected result
- Actual result
- Severity and Priority
- Retest status where applicable

The portfolio includes bugs involving **UI behavior, functional issues, API behavior, server errors, validation failures, data-handling problems, and incorrect HTTP response codes**.

---

## API Testing

The TS-06 API testing work was performed using **Postman** against the Restful-Booker REST API.

Testing was not limited to successful requests. The collection also examines how the API behaves with:

- Invalid input
- Missing fields
- Empty data
- Incorrect data formats
- Unexpected values
- Invalid authentication credentials
- Non-existent IDs
- Invalid update conditions
- Unexpected request structures

The testing was used to evaluate both expected functionality and the API's behavior under invalid or unexpected conditions.

---

## Portfolio and Postman Collection

The **PDF and Postman collection serve different purposes**.

The PDF is the curated portfolio presentation containing selected test cases and bug reports from the overall testing work.

The Postman collection contains the broader testing work for **TS-06**, including tests, bugs, observations, and test scripts that were not all included in the PDF.

This keeps the portfolio document focused while preserving the more extensive API testing work in the collection.

---

## Tools

- **Postman** for API testing
- **Unity** as a testing environment
- **Microsoft Word** for portfolio documentation

---

## Testing Limitations

Some testing scenarios had practical limitations:

- The government portal testing was affected by a **time-limited application window**, which has since closed.
- Restful-Booker is a **public API**, so shared test data and API responses may change between test runs.

These limitations are documented within the portfolio where relevant.

---

## Target Role

This portfolio demonstrates practical, self-directed testing work — including independently identifying and documenting real defects — relevant to **Junior QA / Manual QA / API Tester / QA Analyst / Software Tester positions**.
