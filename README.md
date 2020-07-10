# Keyword Driven Framework for Performance Testing Using Jmeter

A sample JMeter test plan to design your performance test using business keywords. 

Data Driven Framework:
Creating a data driven framework is very easy in JMeter. You come up with a test plan for a business work flow; remove any hard coded test data and parameterize it to work for the data from a file / DB. Most of us would have done this using CSV Data Set Config test element in JMeter.

Keyword Driven Framework:
Keyword driven framework separates the test script implementation from the test case design. We create keywords for each and every business action / functionality of the application. By calling these actions/functions in a specific order, we execute the business workflow.

For Example:

Lets assume we have a web based application in which an user can register to create an account to book flight ticket, view the ticket details, edit, cancel etc. An already registered user can also do all these activities. If the user forgets the credentials, he can use ‘forgot password’ page to get the credentials.

Considering the above requirements, We could create different functions for below functionalities.


 
Register New User
Login
Logout
Book Ticket
Edit Ticket
View Ticket
Cancel Ticket
Forgot Password
Please open jmx file in jmeter for a better understanding. 
