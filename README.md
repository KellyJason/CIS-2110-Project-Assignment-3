# CIS-2110-Project-Assignment-3
Java Project for my CIS 2110 class at MSU Denver

CIS 2110 Project Assignment #3
Name:_________________________________________________________ 
Please note: the first part of this project is to complete Homework 5, which is due at 9:00 AM on Wednesday, NOVEMBER 20!
Project 3 is due at 9:00 AM on Wednesday, December 4!
________________________________________
Problem Description:
Metro Event Sports Specialists (MESS) contracts with many major sports arenas for booth space to sell food, drinks and souvenirs. The accountant for MESS requires a Game Day Report.

A number of employees work at each sports venue during the sport seasons and usually they have two separate booths, one with food and drink and the other with souvenirs at the arenas. 

The game day report is based on a daily sales sheet which first lists the date of the event. Then the sales sheet lists, for each employee who worked on that date, the employee name and their year-to-date sales amount. The employee's entry is followed by all the sales transactions made by the employee on that day.  Each sales transaction includes the sales transaction number, type and amount. 

MESS requires the Game Day Report to show all the information from on the sales sheet. At the end of each sales transaction the report must display the daily running (accumulated) sales amount for the employee.  After each employee's last transaction the report must display the ending (updated) year-to-date sales amount for the employee and the employee bonus amount for the day.  

Additionally after all employees are processed a report summary must show the total sales for food and soft drinks (F), total sales for alcohol (A), total sales for sundries (S), total sales for the day,  total year-to-date sales for all the employees (combined), and the highest single sales amount for the day and the name of the employee responsible for the sale. In the case of multiple instances of the highest only report the first instance. 

Sales transactions are of three types; food & soft drinks, alcohol, and sundries. Food & soft drinks are coded as type 'F', alcohol with type 'A' and sundries with type 'S'.
The employee bonus is 5% of their sales for the day. 
All sales values should be displayed with decimal positions to ensure monetary values are expressed in dollars and cents.

All the numbers listed in the summary are monetary values. 
MESS is willing to enter the data from the Sales Sheet in the order shown in the test data. A zero (0) will be entered for the sales number to indicate the end of entry for an employee. The word "Done" will be entered for the employee name to indicate end of entry for the day.
A (small) subset of data for a typical game day is given below for you to test your models.
Note: You may find Problem 6, the Weekly Attendance Report, in Chapter 4 of the book to be a useful reference. 


CIS 2110 Project #4 Test Data
Metro Event Sports Specialists
Sales Sheet
Date: December 7, 2014
EmpName	YTDSales	SalesNumber	SalesType	SalesAmount
B Ball	10000.75			
		101	A	50.50
		105	F	25.00
		109	A	30.00
		0		
K Off	21000.95			
		102	F	40.40
		106	A	80.00
		0		
C More	20000.35			
		103	A	60.60
		104	S	120.00
		107	A	19.00
		108	S	60.00
		0		
Done				

 
Due Dates and Deliverables for Project 4 Part B:
NOTE: I will not accept any late work after 9:00 AM on Wednesday, Dec 4.  Whatever you’ve got done- turn it in.  I want everyone to be focused on the final project (which is simple) and the final exam.   
•	A Java program which implements the Pseudocode solution (your pseudocode and/or the given pseudocode solution for Homework 5 and includes:
1.	a comment at the beginning of the source code listing your name, a report title or description, and date written
2.	one or more println statements to output the author name and a report title at the beginning of the report.
3.	have a minimum of five methods in the second (non-driver) class. The appMain methods does count towards the minimum. 
Submission Instructions for Project 4 Part B:
Submit your code via Blackboard: 
  
1.	Your code should be sent to me as a text file named project4.txt   This text file should open in MS notepad.      
2.	The primary class in your file (the one that matches the file name) should be called project4YourLastName  (insert your last name, obviously).  
3.	Your primary goal is to create code that runs.  Start by getting all of your methods created and noted with “stubs”-> a stub is a System.out.println() to create an output that shows you the “walk through” of your code.  THEN start to implement the variable manipulations and other logic.  
4.	If you have code that doesn’t work, but you want me to see that you were “close”,  comment out the code that doesn’t work with //fixme!   This way I can see what you were trying to do (I try to be very generous with points, so help me help you!)  
5.	Upload this code file into Blackboard as project4YourLastName.txt.
