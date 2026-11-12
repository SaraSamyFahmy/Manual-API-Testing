# Manual API Testing

## Overview

This project demonstrates manual API testing using Postman and the DummyJSON REST API. It focuses on testing authentication, user profile updates, and API input validation through positive and negative test scenarios.

The project includes test case design, test execution, actual and expected result comparisons, defect reporting, and Postman request organization.

## Tools & Technologies

- Postman
- REST API
- JSON
- HTTP Methods (GET, POST, PATCH)
- DummyJSON API

## Testing Scope

The assignment covers four main testing areas:

1. **Login:** Testing successful and unsuccessful authentication scenarios.
2. **Authentication:** Verifying access to protected endpoints using valid, missing, invalid, and expired tokens.
3. **User Profile Updates:** Testing username and password updates with valid and invalid inputs.
4. **Language & Preferences:** Exploring how the API handles unsupported user profile fields.

## Repository Structure

- `Test-Cases/` – Manual API test cases and execution results.
- `Bug-Reports/` – Reports for failed test cases and unexpected behavior.
- `Observations/` – Documented API limitations and testing observations.
- `Postman/` – Exported Postman collection.

## API Under Test

**DummyJSON**

Base URL: https://dummyjson.com

DummyJSON is a mock API intended for testing and prototyping. Profile updates are accepted and echoed in the response but are not permanently saved on the server.

## Test Documentation

The test documentation includes:

- Test ID
- Test Scenario
- Preconditions
- Test Steps
- Test Data
- Expected Results
- Actual Results
- Pass/Fail Status
- Notes

## Project Purpose

The purpose of this project is to practice manual API testing, understand HTTP response codes, validate API behavior, identify unexpected responses, and document testing results.
