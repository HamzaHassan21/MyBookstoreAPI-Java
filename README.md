BookstoreAPI – Client-Server Architectures Coursework
Author: Hamza Hassan
Student ID: W2044381
Module: Client-Server Architectures (5COSC022W)
University of Westminster

Overview
This project is a complete RESTful API for a fictional bookstore, built entirely in Java using JAX-RS (Jersey) and the Grizzly HTTP server, with JSON used for all data exchange. The entire system runs in-memory, using Java’s HashMap and ArrayList, with no databases or external frameworks (as per the coursework requirements).

The API allows users to manage:

Authors

Books

Customers

Shopping Carts

Orders

It includes robust input validation and fully customized exception handling. All endpoints were tested using Postman with both valid and invalid data.

Project Structure
File/Folder	Description
HamzaHassan_BookStoreAPI_W2044381.zip	Contains the full Java source code of the API (model, resource, exception, main, etc.), with in-depth comments written in first-person to explain logic clearly. It includes custom exception mapping and unique field names for better personalization.
Bookstore_API_Test_Report_HamzaHassanW2044381.docx	A comprehensive report of all test cases run using Postman. This includes both successful and failing scenarios for all CRUD operations, with screenshots, example JSON requests, and expected vs. actual responses.

Features
Fully functional RESTful API using javax.ws.rs and Jersey

Custom exceptions like AuthorNotFoundException, BookNotFoundException, etc.

ExceptionMapper implementation to return clean JSON error responses

In-memory data storage with auto-generated IDs

Detailed code comments and structured logic for easy readability

Manual testing via Postman covering all endpoints

How to Run
Open the .zip file in NetBeans or any IDE supporting Maven.

Ensure Java 17+ and Maven are properly configured.

Clean and Build the project.

Run the Main class to start the Grizzly server.

Test endpoints using Postman at: http://localhost:8080/api/

Demo Video
You can watch my video walkthrough here (including tests and explanation):
YouTube Demo: https://www.youtube.com/watch?v=RR-QPvmMjh8

Testing Report
The Bookstore_API_Test_Report_HamzaHassanW2044381.docx explains:

Each endpoint tested

Valid and invalid test scenarios

Status codes expected and received

Custom exception messages for clarity

