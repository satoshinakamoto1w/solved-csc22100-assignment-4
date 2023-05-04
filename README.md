Download Link: https://assignmentchef.com/product/solved-csc22100-assignment-4
<br>
5/5 - (2 votes)

Consider the Student database schema below.

Students(empID, firstName, lastName, email, gender) Courses(courseID, courseTitle, department) Classes(courseID, studentID, sectionNo, year, semester, grade)

The underlined attributes are the primary keys of their corresponding tables. The value of attribute gender may only be F, M, or U, respectively for female, male, or unknown. The only letter grades allowed in the database are A, B, C, D, F, and W.

Your tasks are to:

<ol>

 <li>Use the data provided in file scheduleSpring2021.txt to populate the Courses andClasses tables. The grades are initially set to NULL.</li>

 <li>Build and test a Java application that [1] connects to the database, [2] creates, [3] populates, and [4] updates the Students, Courses, and Classes Tables. Explicitly specify all the classes imported and used in your Java application. Your application should utilize PreparedStatement objects for the execution of DDL statements and SQL queries.</li>

 <li>Utilize the update functionality in the code to update the student grades, as required.</li>

 <li>Calculate and display the number of students for each letter grade in CSc 22100 [Software Design Laboratory] in the Spring 2021 semester.</li>

 <li>Utilize the Java classes in Assignment 3 to build and display a pie chart showing the proportion of students for each grade. In the pie chart:</li>

</ol>

In-person demonstration of your application is required. The demonstration is scheduled on Thursday, 13 May 2021 during regular class time 2:00 – 3:15 pm.

<ol start="6">

 <li>Each segment has a different color;</li>

 <li>Each segment has a legend showing the corresponding grades and number ofstudents;</li>

 <li>The segments for the grades are displayed in alphabetical order.</li>

 <li>The report should show sample input tables and output table for the stated query and corresponding pie chart for a sufficient amount of input data.</li>

 <li>You may only use JavaFX graphics and your own classes and methods for the operations included. Further,

  <ol>

   <li>The code is applicable to canvases of variable height and width;</li>

   <li>The size of the pie chart is proportional to the smallest dimension of the canvas;</li>

   <li>The segments of the pie chart are filled with different colors of your choice,specified through a MyColor enum reference type.</li>

  </ol></li>

 <li>You may use any Relational Database Management System (RDBMS) of yourchoice.</li>