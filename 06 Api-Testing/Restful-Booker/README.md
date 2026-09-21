Restful Booker API Testing
Project Overview
API testing project created in Postman to demonstrate REST API testing skills, including authentication, CRUD operations, positive and negative testing, and automated response validation.
API: Restful Booker Tool: Postman Testing type: API / Functional / Negative Testing
Scope
The following API functionality was tested:
	•	Authentication
	•	Get all bookings
	•	Create booking
	•	Get booking by ID
	•	Update booking
	•	Partial update booking
	•	Delete booking
	•	Verification of deleted booking
	•	Invalid booking ID
	•	Invalid authentication
	•	Invalid endpoint
Test Coverage
Authentication
	•	Successful authentication
	•	Token generation
	•	Automated token storage using Postman environment variables
	•	Invalid credentials
Booking
	•	Retrieve all bookings
	•	Create a new booking
	•	Verify generated booking ID
	•	Retrieve booking by ID
	•	Full update using PUT
	•	Partial update using PATCH
	•	Delete booking
	•	Verify that deleted booking is no longer available
Negative Testing
	•	Request with non-existent booking ID
	•	Invalid authentication credentials
	•	Invalid API endpoint
Automated Assertions
The Postman collection includes automated checks for:
	•	HTTP status codes
	•	Response body
	•	Response data types
	•	Required fields
	•	Booking ID generation
	•	Updated data
	•	Authentication token
	•	Response time
	•	Deleted resource verification
Environment Variables
The project uses Postman environment variables:
Variable
Purpose
baseUrl
Base URL of the API
bookingId
Stores the ID of the created booking
authToken
Stores the authentication token
bookingId and authToken are generated automatically during test execution.
Test Execution
The complete collection can be executed using Postman's Collection Runner.
Latest execution result:
41 tests passed / 0 failed
Project Structure
Restful-Booker/
│
├── Postman/
│   └── Restful-Booker-API-Testing.postman_collection.json
│
└── README.md
Skills Demonstrated
	•	REST API testing
	•	Postman
	•	HTTP methods: GET, POST, PUT, PATCH, DELETE
	•	API authentication
	•	Environment variables
	•	Automated API assertions
	•	Positive testing
	•	Negative testing
	•	CRUD testing
	•	Response validation
	•	Collection Runner
	•	Git / GitHub
