# Library-Management-System
Java Application for Library Management

Objective/ Vision:- 
A library management software where librarian can add students in database of library, add books in library, issue a book to a student, return book from student, view issued books and available books in the library.                                                                                                                                     
Users of the System:- 
	Librarian                                                                                                                                                                       
Functional Requirements:- 
1.	Can Log In
2.	Sign Up
3.	Log Out
4.	Forgot Password
5.	Can add/view Books
6.	Can Issue Books
7.	Statistics(View issued and returned books)
8.	Student Details
9.	Books Details
Tools to be used:- 
1.	Use any IDE to develop the project. It may be Eclipse /Myeclipse / Netbeans etc (I’ve used Intellij).
2.	MySQL for the database using Wamp server.
Front End and Back End:- 
1.	Front End: Java Swing
2.	Back End: MySQL
How to run this project:- 
1.	Clone this repository
2.	Import the project on Intellij
3.	Add the jar files (jcalendar-tz-1.3.3-4, rs2xml and mysql-connector-java-8.0.23) into library section of the project	Download and install wamp server.Now, Start wamp server and create a database as project1 and create the tables under this database. To create the tables you can follow these below MySQL query statements--
	  a) create table book(book_id varchar(10), name varchar(40), isbn varchar(20), publisher varchar(30), edition varchar(10), price varchar(10), pages varchar(10));
	  b) create table student(student_id varchar(10), name varchar(25), father varchar(25), course varchar(10), branch varchar(10), year varchar(10), semester varchar(10));
    c) create table issueBook(book_id varchar(10), student_id varchar(10), bname varchar(40), sname varchar(40), course varchar(20), branch varchar(10), dateOfIssue varchar(30);
	  d) create table returnBook(book_id varchar(10), student_id varchar(10), bname varchar(40), sname varchar(40),course varchar(20), branch varchar(10), dateOfIssue varchar(30), dateOfReturn varchar(30));		
	  e) create table account(username varchar(20), name varchar(25), password varchar(25), sec_q varchar(25), sec_ans varchar(25));
    
    Now, we are ready to run this project!
    
    Thank You for reading this discription! If you find it useful follw me and give a star this repo.
