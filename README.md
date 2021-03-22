# P-300-181-115-034-181-115-013-

## Introduction: 

Information Technology has revolutionized the life of human beings and has made the lives easier by the several of application. In the light of the rapid changes with the use of IT, there are many tools, technologies and systems have been produced and invented. In the modern world, time is so if there are many processes taken place at same time within a place there is a need for integration of all the processes, creation of paperless environment also ensures efficient task management. 


Nowadays all the businesses are shifting to computer based system. The purpose to having a computer based system is, it helps to increase the market share and it’s very easy for customers to use. It is increasing the demand amount the customer. This project is concerned with developing Online Library Management System using PHP and Laravel framework. It’s basically made to track records of find books, issued, find students, etc. In this system the library Management becomes more efficient and easier to handle with its reliable system components.

---

## Objectives: 

The aim of the project is to prepare a web based automation system for the library with Online Public Access Catalogue (OPAC). And automating the existing system to keep a record of transactions that have taken place on the system.

---


## Methodology: 

Library is the place where information and books are stored. It is the place where people from all fields used the books and information required for them. But for that the purpose since long time the manual system was followed during operation using the library card. But with the increasing demands of technology in various fields are forcing to stop the manual system in the library operation. So to fulfill the increasing demands of the library management software has been developed.

---

## Motivation of this project: 

To store all information in the database from where user will place their query and get the results on this basis of their query. Only valid users will be able to access this Library Management System. Through this Library Management System it will easy to manage accounts and various details of particular student and librarians working under library along with the records of book.          

---

## Scope: 

This application can be used by any library to maintain the student records, daily transactions of books. There are other opportunities as well: 

1.	Admin login 
2.	Facility to reserve books that are available 
3.	A status pages for all users to view books reserved by them
4.	Facility to cancel the reservation for a book made earlier 
5.	A status pages for admin to view currently issued logs.

---

## Future scope of application: 

This application can be easily implemented under various situations. We can add new features as and when we require. Reusability is possible as and when require in this application. There is flexibility in all the modules.

---

## Library Management System in Laravel: 

A Library Management System is a project that manages and stores books information electronically according to student’s needs. The system helps both students and library manager to keep a constant track of all the books available in the library. It allows both the admin and the students to search for the desired book. It becomes necessary for all institutions to keep a continuous check on the books issued and returned. 

---

## Background of project: 

Library Management System is an application which refers to library systems which are generally small or medium in size. It is used by librarian to manage the library using a computerized system where he/she can record various transactions like issue of books, return of books, addition of new books, addition of new students etc.
Books and student maintenance modules are also includes in this system which would keep track of the students using the library and also a detailed description about the books a library contains. With this computerized system there will be no loss of book record or member record which generally happens when a non-computerized system is used.
All these modules are help able to help librarian to manage the library with more convenience and in a more efficient way as compared to library systems which are not computerized.

---

## Module Description: 

Online library management system divided in two modules –

1.	Admin 
2.	Student

---

 	Admin Features: 
   
1.	Librarians can be given there authorized login ID and password without which the system can’t be accessed or you can login by registering a new id by signing up.
2.	After login librarians can search for a specific book, book issue or student from the home panel. Librarian can search student by using their student ID.
3.	Librarians need to make an entry for the new books. To automate the process they simply need to enter the number of issues, then the issue ID for each book issue is generated automatically.
4.	Another responsibility of a librarian is to approve students in situations where approval is needed, i.e. where documents are to be verified or some manual work. Librarians have a panel to simply approve/reject students and to view all approved students. The librarian ID is stored alongside each approved/rejected student to keep track.
5.	The most important function of any library is to issue and return books. This system includes a panel to view all outstanding logs and a super simple panel to issue and return books for all librarians.

---

 	Student Features:
   
1.	Students can only access limited features, i.e., public access level features which include searching a book and student registration form.
2.	Student can register yourself and after registration they will get student ID.
3.	Student can view issued book

---

## Technologies Used:

1.	Framework: Laravel
2.	Language: PHP 
3.	Database: MySQL

---

## Initial interface 

![Screenshot (356)](https://user-images.githubusercontent.com/73945266/112022260-54bf3000-8b5c-11eb-8c87-e9a195e2a1ed.png)


---

## Block diagram

![Screenshot (346)](https://user-images.githubusercontent.com/73945266/111470276-e17b7f80-8751-11eb-99e4-e212ce81de4e.png)

---

## Admin interface 

![Screenshot (348)](https://user-images.githubusercontent.com/73945266/111470792-6bc3e380-8752-11eb-8e7f-58b543b34e0a.png)

---

## Summary: 

The Library Management System needs to be computerized to reduce human errors and to increase the efficiency. The proposed Library Management System in this proposal will be a computerized management system developed to maintain all the daily work of library. Library management systems are designed to store all the information about books and members.
The main focus of this project is to lessen human effort and encourage efficient record keeping.


---


## How to install and run my project on your local system

- Clone the repository with git clone https://github.com/JHS-Sujel/Online-Library-Management-System-P-300
- cd Online Library Management System (P-300)
- Run composer install or update 
- Add your database config in the .env file
- Create a new database in your localhost 
- Table create: Run php artisan migrate
- Create default user for system with: php artisan db:seed.    --seed__ (it has some seeded data for your testing)
- Run php artisan key:generate
- Run php artisan config:clear
- Run php artisan serve (if the server opens up, http://127.0.0.1:8000, then we are good to go)
- Login info: email- jhs pass- 12345678

---

## License

   Basically, feel free to use and re-use any way you want.
