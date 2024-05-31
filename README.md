# Database-Operations-and-Interactions

In this assignment, we will learn about the following technologies:
•	Maven - https://maven.apache.org/what-is-maven.html
•	JDBC - https://docs.oracle.com/javase/tutorial/jdbc/basics/index.html
To complete the assignment, you need to:
•	Clone/download the starter code using the provided link.
•	Install MySQL Server and Workbench on your computer.
•	Create a connection and schema through Workbench.
•	Test the connection to the database using the built-in utility in your IDE, as shown in the following video.
Task description:
•	You need to familiarize yourself with the starter code and modify the application to interact with the database using the User class, and test your methods with pre-written JUnit tests. By the end, all tests should be passed. It is allowed to view the implementation of the tests.
•	To run a test, you need to find the class in the "test" folder and right-click on it, selecting Run "Class Name".
•	The UserHibernateDaoImpl class is not modified as part of this task (it remains empty).
The User class represents an entity with the following fields:
•	Long id
•	String name
•	String lastName
•	Byte age
The architecture of the application is designed with a focus on the MVC design pattern (partially, as it is not a web application).
Requirements for application classes:
•	DAO/Service classes should implement corresponding interfaces.
•	DAO class should have an empty/default constructor.
•	All fields should be private.
•	Service should reuse methods from DAO.
•	Handling of all exceptions related to database operations should be done in DAO.
•	The Util class should contain logic for configuring the database connection.
Required operations:
•	Creating a table for Users - should not throw an exception if such a table already exists.
•	Dropping a table for Users - should not throw an exception if the table does not exist.
•	Clearing the contents of the table.
•	Adding a User to the table.
•	Removing a User from the table by id.
•	Getting all Users from the table.
Algorithm of the application
The Main class's main method should perform the following operations:
•	Creating a table for Users.
•	Adding 4 Users to the table with data of your choice. After each addition, there should be a console output (User with name - name added to the database).
•	Getting all Users from the database and printing them to the console (toString method should be overridden in the User class).
•	Clearing the Users table.
•	Dropping the Users table.
Please, submit the link to the GitHub repository with the solution to the task.
