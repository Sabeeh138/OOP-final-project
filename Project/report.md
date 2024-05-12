# PF-final-project
## made by:



## This project is a hospital management system.

## project proposal:
<p>the idea was to create a program that can cater to the needs of both management staff and the people coming to the<br>
   airport. A layer of security is to be added to ensure a normal user cant access the admin panel and the data in the<br>
   file cant be manually changed. In addition to that data recycling functionality was to be added so that any and all<br>
   records deleted are stored in another recycled file and that data could be deleted later on. Attractive prompt<br>
   messages to be displayed to make the interface more user friendly and should have enough data manipulation options for<br>
   the management. Hospital Management System (HMS) is a software solution designed to streamline and automate the administrative <br>
   and operational processes within a hospital or healthcare facility. This proposal outlines the key features, objectives, and <br>
   implementation plan for developing an HMS.</p>

## Features:

### Patient Management: 
Allow receptionists to register new patients, schedule appointments, and maintain patient records.
### Doctor Management: 
Enable doctors to manage their schedules, prescribe medications, and access patient information.
### Staff Management: 
Maintain records of hospital staff, including doctors, nurses, and administrative personnel.
### Inventory Management: 
Track inventory levels of medical supplies, equipment, and pharmaceuticals.
### Billing and Accounting:
Generate and manage patient bills, invoices, and financial transactions.
### Reporting and Analytics: 
Provide insights into hospital performance, patient demographics, and resource utilization.

## Logic Used:
### Object-Oriented Approach:
The program is structured using object-oriented programming concepts, with classes representing different entities such as Person,<br>
Staff, Patient, Doctor, Nurse, Receptionist, and Store Manager.

### Inheritance:
Inheritance is utilized to create specialized classes like Staff, Doctor, Nurse, Receptionist, and Store Manager,<br>
inheriting common attributes and methods from the Person class.

### Polymorphism:
Function overriding is used in the Person and Staff classes where the Info() method is overridden to gather specific<br> 
information for each type of staff member.

### File Handling:
The program extensively uses file handling to store and retrieve data about patients, doctors, nurses, receptionists,<br>
and store managers. It uses binary files to store objects of respective classes.

### User Input Handling: 
The program handles user inputs for various tasks such as entering patient information, doctor details, nurse details,<br>
receptionist details, and store manager details. It includes input validation and error handling.

### Menu-Driven Interface:
The program provides a menu-driven interface for different types of users (admin, receptionist, doctor, store manager) to <br>
perform specific tasks like adding, modifying, or deleting records, prescribing medicine, ordering products, etc.

### Password Authentication:
Basic password authentication is implemented for admin and receptionist roles to restrict access to sensitive functionalities.

### Data Display:
Data is displayed in an organized format using functions like display_all(), display_p(), display_d(), display_n(), and display_s()<br>
for patients, doctors, nurses, receptionists, and store managers, respectively.

### Data Modification and Deletion: 
Functions are provided to modify and delete records for patients, doctors, nurses, receptionists, and store managers based on user input.

### Ordering Products: 
The store manager can order products and supplies, with functionality to display the ordered items and their bills.

   
