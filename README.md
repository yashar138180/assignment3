\# University Course Management System



\## Description



This project is a University Course Management System built with JavaScript.



The project demonstrates the use of:



\- ES6 Classes

\- Asynchronous callbacks

\- setTimeout

\- Object property descriptors

\- Array methods such as map, filter, reduce, forEach, and some

\- Higher-order functions



\## File Organization



\### models.js

Contains the Student class.



The Student class stores the student's ID, name, and courses.

The ID is defined using Object.defineProperty() and is read-only.



It also contains:

\- addCourse()

\- getAverage()



\### database.js

Simulates an asynchronous database request.



The fetchStudents() function uses setTimeout() with a 2-second delay and returns student data through a callback.



\### analytics.js

Contains functions used to analyze student data:



\- calculateClassAverage()

\- findTopStudent()

\- filterStudents()



\### main.js

The main executable file.



It:

\- Fetches student data

\- Converts raw data into Student objects

\- Tests ID immutability

\- Calculates the average for Course 101

\- Finds the top student

\- Filters students enrolled in Course 102



\## How to Run



Make sure Node.js is installed.



Open a terminal inside the project folder and run:



node main.js



\## Challenges



One challenge was making the student ID immutable. This was solved using Object.defineProperty() with writable and configurable set to false.



Another challenge was working with asynchronous data. The student data is returned after a delay, so the calculations must be performed inside the callback.



I also practiced using array methods such as map(), reduce(), filter(), and some() to process the student data.

