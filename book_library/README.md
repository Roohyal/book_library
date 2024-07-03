# book_library
Book Library
Problem Description
The Book Library project models a library system where students and teachers can borrow books. The system manages the borrowing process, ensuring that the rules for priority and availability are followed.

Key Requirements
Borrowing Rules:

When a book is no longer available in the library, the system should return ‘book taken’.
There can be multiple copies of the same book in the library.
Implementation 1:

Books are given by the Librarian on a first-come, first-served basis.
Teachers have priority over students when requesting the same book.
Senior students have priority over junior students when requesting the same book.
Implementation 2:

Books are given by the Librarian on a first-come, first-served basis, regardless of the requester's role (teacher, junior, or senior student).
Project Goals
Automated Testing:

Write automated tests to ensure the functionality of the library system.
Organized Structure:

Organize the folders to house both the code base and the tests.
Test-Driven Development (TDD):

Write tests to cover all methods before development begins.
Logical Assumptions:

Make logical assumptions where necessary to complete the model.
Project Structure
The project follows a structured approach to ensure maintainability and scalability.

Folders Organization
src/main/java: Contains the main application code.
src/test/java: Contains the test cases.
Key Classes
Library: Manages the collection of books and the borrowing process.
Book: Represents a book in the library.
User: Represents a user of the library (Student, Teacher).
Librarian: Manages the borrowing process, ensuring the rules are followed.
Concepts Used
Encapsulation
Inheritance
Polymorphism
Interfaces/Abstract Classes
Single Responsibility Principle
Abstraction
Aggregation
Composition
Generics
Collections
Exception Handling
UML Diagram
A UML diagram should be included to represent the classes and their relationships.

Priority Queue
Implement a PriorityQueue class where applicable to manage the borrowing process based on priority rules.

Development Process
Step 1: Write Automated Tests
Write tests to cover all the methods and conditions.
Ensure that tests cover edge cases and different scenarios.
Step 2: Organize Folders
Create a logical structure to separate the code base from the tests.
Step 3: Implement Methods (TDD)
Implement the methods based on the tests.
Ensure that the code follows the specified requirements.
Step 4: Make Logical Assumptions
Fill in gaps with logical assumptions to complete the model.
Evaluation Criteria
Classes
UML Usage:

Use UML to represent the class structure.
Visibility Modifiers:

Use appropriate visibility modifiers for class members.
OOP Concepts:

Implement encapsulation, inheritance, polymorphism, interfaces/abstract classes, single responsibility, abstraction, aggregation, composition, generics, collections, and exception handling.
Priority Queue:

Use or implement a PriorityQueue class where applicable.
Test Coverage
Method Coverage:
Ensure that tests cover all methods.
Condition Coverage:
Ensure that tests cover the conditions and procedures employed by the methods.