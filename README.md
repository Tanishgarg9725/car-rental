# Car Rental System
This C++ program implements a car rental system that allows both administrators and customers to interact with a car rental service. Below is an overview of the functionalities provided by the program:

Features
Admin Functionality:

Add Cars: Administrators can add new car models with their respective mileages to the list.
Delete Cars: Administrators can delete existing car models from the list by specifying their index.
Display Cars: Administrators can display all available car models along with their details.
Customer Functionality:

Login: Customers can log in using a password to access rental services.
View Cars: Customers can view the list of available car models and select one for rental.
Rental Details: Customers provide the rental period (in days) and receive a detailed invoice for the rental, including the total cost calculated based on the car’s mileage.
Technical Details
Data Structures: The program uses a doubly linked list to manage the car models. Each node contains the car model name, mileage, and pointers to the next and previous nodes.
User Interaction: The program uses console input and output for user interaction, providing prompts and reading responses.
File Handling: Details of car models are read from text files (A.txt, B.txt, C.txt) to display additional information about the selected car model.
Inheritance: The rent class inherits from the customer class, demonstrating object-oriented principles.
How to Use
Admin Access: Use the password admin to log in as an administrator and manage car data.
Customer Access: Use the password 1234 to log in as a customer, view available cars, select a car for rental, and generate an invoice.
This program provides a basic yet functional car rental management system, demonstrating core concepts of C++ including classes, inheritance, file handling, and data structures.





