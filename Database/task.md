# DataBase Task
hello guys i wish you gained some solid knowledge about databases know
# Table of Contents
[0- dataset](#dataset)   
[1- part 1](#sql)   
[2- part 2](#register)   
[4- submission](#submit)   
[3- solution](#solution)   

<a id="dataset"></a>

## Dataset

we will use same emplyee sample data base [here](./readme.md)

you can connect to it on the server using this command ```mysql -h mysql-162195-0.cloudclusters.net -P 19994 -u test_user -p``` then enter the password but unfortunately this server is free trial and ends on 5/2/2024.   
so we encourage you to install it locally    
it's so easy and you need only 2 steps    
1- clone this [repo](https://github.com/datacharmer/test_db)    
2- run this command inside the cloned folder ```mysql -h localhost -u root -p < employees.sql``` then enter you password.   
you know have an instance of the database on your machine.

<a id="sql"></a>

## Part 1: SQL problems
let's practice some sql queries.

1- show employee first name , last name and salary amount for top 5 salaries in the company.

2- Select all female employees in the the year 2000 or after.

3- Determine how many managers are in the database

4- Retrieve list of all female employees whose first name is either 'Kellie' or 'Aruna'

5- Find the number of Male (M) and Female (F) employees in the database.

***(bonus)***
\
<img width=200 align="right" src="./images/Q6.png">
6- show top 5 salaries in each department, return employee first name, salary, department name order results by department then by salary   
you can expect results as in image.

<a id="register"></a>

## Part 2: 
Ok our activities committee has a big problem they are lost in the dozens of excel sheets, so they decided to get help from you as a software expert.   
they wanna make a registration system for the events.   
if you attended any of our events/courses before first you fil la form to register in the event then in the event dat the reciptionist take you attendence.   
so a system like that need to store user data and event data.   
store ??????????????????????    
ok you got it we need a database here, so let's model our database first, we need to store this data:      
User:
- UserID
- First Name
- Last Name
- Email
- Phone Number
- Any other relevant information (e.g., address)   

Event:
- EventID
- Event Name
- Event Date
- Event Location
- Event Description
- Event Manager
- Any other relevant information

TeamMember:

- MemberID
- UserID
- CommitteeID
- Any other relevant information (e.g., role in the team)

TeamCommittee:

- CommitteeID
- CommitteeName
- HeadID
- Any other relevant information (e.g., committee name)

Registration:

- RegistrationID
- UserID
- EventID
- Registration Date
- Any other relevant information (e.g., payment details, registration status)

Attendance:

- AttendanceID 
- UserID 
- EventID 
- Attendance Date
- Any other relevant information (e.g., check-in time)   

ok show us your modeling skills and give us ERD and Relational model.

<a id="submit"></a>

## Submission
Use this [form](https://forms.gle/cnPHZnZx25gaNdBg8) to  submit before deadline.

Deadline is tuesday 6/2/2024 before 12.AM (+2 GTM)

<a id="solution"></a>

## Solution
[here]()   
to be posted after deadline.

