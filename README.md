HOW TO USE EMPLOYEE PROJECT
Create database in PostgreSQL, All the connectivity is for Postgre with database name as demo and username as postgres and password as postgres
To use mysql or H2, two application.properties files have been added data.sql for H2 is also added.
    Run the Spring application with localhost:8080/. User will see the following Page. 

This is Developed in Springboot and the frontend is on thymeleaf. 
Users can see pagination in the screenshot at bottom of page.
Pagination will come into effect when there are more than 5 records. 
Users can add employees by clicking the top left button.
When Users click add employee below form will be open.

When all the information is entered only then the save employee button will be enabled. 
Phone Number Validation is enabled i.e. only numbers can be entered otherwise it will not submit the form.
Salary must be greater than 0 only then the Save Employee button will be enabled. 
There is a back button in the bottom to take the user back to the List Page. 
When the record is successfully saved it will also take the user back to the List Page and show the new inserted record as shown below.


When the user clicks the delete button it will delete the record and load the page to show that record is now not on the list page. 
When user click the update button, a new form will be opened as shown below which will load all the data of the employee which is selected. 
 

Users can update the information and click the save button due to which the existing record will be updated. 
