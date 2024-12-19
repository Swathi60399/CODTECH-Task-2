Name: SWATHI N V

Company: CODTECH IT SOLUTION

ID: CT6WDS2542

Domain: 25 NOV 2025 TO 06 JAN 2025

Mentor: 

Overview of the Project
Project: Library Management System
![image](https://github.com/user-attachments/assets/86468f37-8704-4658-9651-5e0b9a9fb9e2)

Objective
The objective of this program is to create a Library Management System that enables users to manage library items such as books, magazines, and DVDs. It supports adding items, checking them out, returning them, managing overdue fines, and searching for items.

Key Activities
1.	Add New Items
    o	Users can add books, magazines, or DVDs to the library.
    o	Each item has attributes like title, author, category, and status (checked out or not).
2.	Checkout Items
    o	Users can check out an item by entering the title and the received date and time.
    o	The program calculates the due date (14 days loan period by default) and marks the item as checked out.
3.	Return Items
    o	Users can return checked-out items by entering the return date and time.
    o	The program updates the status of the item to "not checked out."
4.	Manage Overdue Fines
    o	The program calculates overdue fines for items not returned by their due date.
    o	Fine: $1 per day for overdue items.
5.	Search for Items
    o	Users can search for library items using keywords from the title, author, or category.
    o	The program displays matching items with their details and current status.
6.	Exit the System
    o	Users can exit the system when done.

Technologies Used
1.	Python Programming Language
    o	Provides object-oriented design for creating classes and methods.
    o	Built-in modules like datetime help handle dates and times efficiently.
2.	OOP Principles
    o	Encapsulation: Library items and their functionalities are encapsulated in classes like LibraryItem, Book, Magazine, and DVD.
    o	Inheritance: Book, Magazine, and DVD inherit from the base class LibraryItem.
    o	Polymorphism: The checkout and return_item methods can handle different item types dynamically.
3.	Datetime Module
    o	Used to manage dates and times for tracking loan periods, due dates, and return dates.
4.	Command-Line Interaction
    o	Allows users to interact with the system through a menu-driven interface.
