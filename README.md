# Projects-on-API-testing-

## Project #1:SOAP NumToWord Conversion - Postman Collection

# Overview
This project contains a Postman collection for testing the **NumberToWords* SOAP API hosted by DataAccess. The API converts numerical inputs into their corresponding word representations.

# Key Features
- Validates positive test cases with proper numerical input.
- Handles edge cases like invalid formats, alphanumerical inputs, and empty inputs.
- Includes negative test cases to evaluate error responses for unsupported inputs.

## Files
- `Project #1-SOAP NumToWordConversion.postman_collection.json`: The Postman collection containing all the test cases for the SOAP API.

## API Information
- *Base URL:* `https://www.dataaccess.com/webservicesserver/NumberConversion.wso`
- *Method:* POST
- *Content-Type:* `application/soap+xml`

# Test Scenarios
1. *Positive Test Case:*
   - Input: Valid number (e.g., `503`).
   - Expected Response: Returns "Five Hundred Three."

2. *Negative Test Cases:*
   - Invalid numerical formats (e.g., `1234.12`).
   - Special characters (e.g., `@`, `&(*`).
   - Alphanumerical inputs (e.g., `123ABC`).
   - Empty or whitespace inputs.
   - Boolean values (`true`/`false`).

# Newman Summary Report: 
file:///C:/Users/sasha/OneDrive/Desktop/swetha/thetestingacademy%20Aut%20cours/newman%20API%20html%20run%20report/API%20testing%20-SOAP%20project1-2024-10-15-01-49-50-542-0.html

## Project #2: API  Documentation (Restful booking) collection
# Restful Booking API - Postman Collection
This project contains a Postman collection for testing and interacting with the Restful Booker API, a public API used for booking-related operations.

# Overview
The Restful Booker API provides endpoints to perform booking operations such as creating, retrieving, updating, and deleting bookings. This project includes automated tests and scenarios to validate these operations under various conditions.

# Key Features
Create new bookings with valid and invalid data.
Retrieve booking details by ID or other query parameters.
Update and partially update booking information.
Delete bookings.
Integration scenarios for end-to-end API workflows.
Negative test cases to handle invalid requests.
Files

# The exported Postman collection containing:
Test cases for booking creation, retrieval, update, and deletion.
Negative test cases such as invalid URLs, invalid data formats, and empty fields.
Integration test scenarios combining multiple steps.

# Included Scenarios
# Test Cases
# Create Booking:
Valid and invalid payloads.
Special characters, long names, and edge cases.
# Retrieve Booking:
Fetch all booking IDs.
Fetch bookings by specific query parameters (e.g., first name, last name).
# Update Booking:
Full and partial updates.
Using invalid data and unauthorized requests.
# Delete Booking:
alid and invalid booking IDs.
Integration Scenarios
# Multi-step workflows combining:
Booking creation.
Updating or deleting the booking.
Verifying changes with GET requests.
# API Documentation
The API being tested is hosted at: Restful Booker API.

Endpoints Overview
Method	Endpoint	Description
POST	/booking	Create a new booking.
GET	/booking	Retrieve booking IDs.
GET	/booking/{id}	Retrieve booking details.
PUT	/booking/{id}	Update an existing booking.
PATCH	/booking/{id}	Partially update a booking.
DELETE	/booking/{id}	Delete a booking.

# License
This project is open-source and available under the MIT License.

## Project #3: Non API Documentation (AwesomeQA) collection
# Non-API Documentation Testing - AwesomeQA

# Overview
This project contains Postman requests for testing the non-API functionalities of the **AwesomeQA* platform, such as account registration and login workflows. The testing involves mimicking front-end operations through HTTP requests.

# Key Features
- Simulates user actions like registration and login using POST requests.
- Tests form data submission with various scenarios.
- Validates server responses for successful and unsuccessful attempts.

# Workflow Overview
# 1. *Account Registration
- Endpoint: `https://awesomeqa.com/ui/index.php?route=account/register`
- Method: POST
- Headers: Includes `Accept`, `Content-Type`, `User-Agent`, and cookies.
- Form Data:
  - First name, last name, email, telephone, password, and agreement.

# 2.Account Login
- Endpoint:`https://awesomeqa.com/ui/index.php?route=account/login`
- Method: POST
- Form Data:
  - Email and password for authentication.

## How to Contribute
Contributions for improving testing scenarios, adding edge cases, or expanding the test coverage are welcome. Fork the repository and create a pull request.

