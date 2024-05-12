# PF-final-project
## made by:
Muhammad Sabeeh 23K-0002<br>
Syed Huzaifa Ali 23k-0004<br>
Areeb Hussain 22K-4042<br>
Minhaj Uddin 21K-3074<br>

## This project is a hospital management system. 
<br>

## project proposal:
<p>The idea was to create a program that can cater to the needs of both management staff and the people coming to the<br>
   airport. A layer of security is to be added to ensure a normal user cant access the admin panel and the data in the<br>
   file cant be manually changed. Attractive prompt<br> messages to be displayed to make the interface more user
   friendly and should have enough data manipulation options for<br>
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

## It has 2 main sections:

### admin panel:
1. uses a password to login to admin panel
2. can add staff members details and their information to a binary file (so data cant be manually changed from the file)
3. can view a list of all staff members from a binary file (so data cant be manually changed from the file)
4. can search for specific staff member using their id number
5. can edit specific information for staff members that have already been saved to the file
6. can delete a data from the file and store that data in a recycled file.
7. can display the list of all the patients added in the user panel and their data (added on sir's behest)
8. exit the program with a prompt message

### user panel:
1. Patients can register themselves or be registered by hospital staff and update personal info
2. View and manage appointments, including scheduling, rescheduling, and canceling appointments.
3. Access and download medical reports, prescriptions, and discharge summaries.
4. order products and supplies through the store manager menu for the prescribed meds of the patient
5. exit the terminal with a attractice designed prompt message.

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

 ## Problems faced:
 1. problem that it didnt read the patient id when trying to prescribe a medicine through doctor menu
 2. system issue where when we tried to exit the admin system, it didnt go back to the main screen.

## possible improvements:
1. Implementing a GUI using libraries like Tkinter or PyQt would make the system more user-friendly and visually appealing.<br>
This would allow users to interact with the system through buttons, text fields, and other graphical elements instead of just the console.
2. Implement stronger password hashing techniques and encryption methods to enhance security for user authentication.
3. Enhance error handling mechanisms to provide more informative error messages and guide users in resolving issues effectively.
4. Implement search and filtering capabilities to allow users to easily find specific records based on criteria such as patient ID, doctor name, or appointment date.
