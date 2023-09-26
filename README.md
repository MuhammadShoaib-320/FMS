Feedback Management System (FMS)

In FMS we have used Repository Pattern. In infrastructure layer we have DTO's and Implementations of Crud Operations for both Models Company and Feedback. 
In FMS Core Layer we have 2 Entities Feedback and Company . In FMS API Layer we have 2 controller for both entities and also logs folder to maintain logs

below are the implementation that includes in our FMS Project 
1. Layered Architecture
2. Code First Approach
3. Crud Using Web API
4. Middleware
5. Custom Header
6. Logging 


Features
List of features:

1. Create, Read, Update, and Delete (CRUD) operations for companies and feedback entries.
2. User-friendly web interface for administrators.
 

Our ERD Diagram for FMS Project 

![FMS ERD Diagram](ERD_DB.png)

The Feedback Management System exposes the following API endpoints:(Controllers)

Companies:

GET /api/companies: Retrieve a list of all companies.
GET /api/companies/{id}: Retrieve a specific company by ID.
POST /api/companies: Create a new company.
PUT /api/companies/{id}: Update an existing company.
DELETE /api/companies/{id}: Delete a company.

Feedback:

GET /api/feedback: Retrieve a list of all feedback entries.
GET /api/feedback/{id}: Retrieve a specific feedback entry by ID.
POST /api/feedback: Create a new feedback entry.
PUT /api/feedback/{id}: Update an existing feedback entry.
DELETE /api/feedback/{id}: Delete a feedback entry.


The Infrastructure Layer serves as the data access and storage component of the Feedback Management System, providing the necessary interfaces, implementations,
and DTOs to interact with the database and manage Company and Feedback data. These components are crucial for maintaining the integrity and accessibility of your data.
