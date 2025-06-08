BookstoreAPI – Client-Server Architectures Coursework
Author: Hamza Hassan
Student ID: W2044381
Module: Client-Server Architectures (5COSC022W)
University of Westminster

Overview
This project is a complete RESTful API for a fictional bookstore. It is built in Java using JAX-RS (Jersey) and the Grizzly HTTP server. All data is exchanged using JSON, and the entire system is in-memory only, utilizing HashMap and ArrayList — no external databases or frameworks, per coursework requirements.

Functionality
The API supports full CRUD operations for managing:

 🧑‍💼 Authors

📘 Books

👤 Customers

🛒 Shopping Carts

📦 Orders

  Features
RESTful architecture using javax.ws.rs and Jersey

In-memory data storage with auto-incrementing IDs

Custom exceptions (AuthorNotFoundException, BookNotFoundException, etc.)

Centralized exception handling using ExceptionMapper

Robust input validation with user-friendly JSON error messages

Thorough inline comments (first-person perspective)

Postman-tested endpoints with both valid and invalid input scenarios

📁 Project Structure
File/Folder	Description
HamzaHassan_BookStoreAPI_W2044381.zip	Full source code, organized into model, resource, exception, and main packages. Includes in-depth first-person comments.
Bookstore_API_Test_Report_HamzaHassanW2044381.docx	A full test report covering all CRUD endpoints with valid and invalid data, screenshots, and JSON examples.

 How to Run
Extract the .zip file and open the project in NetBeans or any Java IDE with Maven support.

Ensure Java 17+ and Maven are installed and configured.

Clean and Build the project using your IDE or mvn clean install.

Run the Main.java class to start the Grizzly HTTP server.

Access endpoints using Postman at:
http://localhost:8080/api/

Testing Summary
Detailed test results are provided in the .docx report:

Each API endpoint tested individually

Valid and invalid scenarios

HTTP status codes compared (expected vs actual)

Custom exception messages demonstrated (e.g. “Book with ID 99 not found”)

Demo Video
 Watch a full video walkthrough including code explanation and testing:
YouTube Demo

Final Notes
This API was built from scratch with clarity and modularity in mind.

All logic was explained in comments using a first-person style for better understanding.

Testing was carried out thoroughly to ensure the API behaves predictably.

