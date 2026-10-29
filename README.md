# Payment API Testing Portfolio

## Project Overview
This project demonstrates my API testing skills using Postman. It includes positive and negative test scenarios, response validation, and basic automated assertions.

## Objective
To practice API testing concepts relevant to QA roles, including:
- HTTP methods and status codes
- Response body validation
- Positive and negative testing
- Basic test automation using Postman scripts
- Validation of API response fields

## Tools Used
- Postman
- JSONPlaceholder REST API
- JavaScript (basic Postman assertions)
- GitHub

## Test Scenarios

| Test ID | Scenario | Expected Result | Observed Result |
|---|---|---|---|
| API_GET_001 | Retrieve user details | HTTP 200 and valid user details | Passed |
| API_POST_001 | Create a test post | HTTP 201 and response fields match the request | Passed |
| API_NEG_001 | Submit a post with an empty title | Verify whether the API rejects the empty title | API returned HTTP 201 and accepted the request |
| API_GET_002 | Retrieve user details for user ID 3 | HTTP 200 and response ID is 3 | Passed |
| API_NEG_002 | Retrieve a nonexistent user using ID 9999 | HTTP 404 and empty response body | Passed |

## Test Automation
Postman assertions were used to validate:
- HTTP status codes
- Presence of the response ID
- Title matching the submitted request
- User ID matching the submitted request
- Negative testing for nonexistent users (HTTP 404 and empty response body)

## Important Limitation
This project uses JSONPlaceholder, a public mock REST API. It is a practice project, not a real payment processing system. The empty-title scenario demonstrates how to observe and document API behavior; it is not a confirmed defect unless the API specification requires the title to be mandatory.

## How to Run
1. Download the Postman collection JSON file from this repository.
2. Open Postman.
3. Import the downloaded collection.
4. Select a request and click **Send**.
5. Review the response and test results.

## About Me
QA professional with 6.7 years of experience in banking and payments domain testing, including functional, regression, integration, and API testing.

This portfolio is part of my ongoing professional development in API testing and modern QA practices.
