Olivia Horace  
Homework 3  

1. What two kinds of things must a software requirements specification contain?  
A software requirements specification document describes what a product must do and the constraints on the product. These constraints usually include deadlines, aspects regarding portability and what systems software should be ran on, reliability, as well as response time.  

2. Give an example of an ambiguous requirement in English (that is, using a natural language). Explain
the ambiguity.  
Ex: The customer data file should load quickly.  
This requirement is ambiguous because “quickly” is a relative term. There is no indication of how quickly the data file should load. This requirement could be made better by including a specific amount of time like “10 seconds” or “5 seconds”.  

3. Consider the domain of processing student grades. Draw a simple data flow diagram of the process.
Create the drawing as a PDF and upload the file to your Github repository. Explain the drawing in
English as your answer to this question.  
This drawing contains a data source which is Student. The process is named Calculate_Grades. It takes as inputs Student_Classes and Student_Grades. It then processes this data to calculate the students grades which is passed back to the data source Student.  
 
4. Consider the domain of an online shopping cart. Draw a simple finite state machine of the process.
Create the drawing as a PDF and upload the file to your Github repository. Explain the drawing in
English as your answer to this question.  
The finite state machine has two main states: an empty cart and order made. In between these two are the inputs of adding items, selecting 'Checkout, and entering payment information. As long as the payment information entered is authorized, then the order will be made. If it is not authorized then the order will not be completed.  

5. Consider the domain of a database with customer, products, and orders tables. Draw a simple entity-
relation diagram of the database. Create the drawing as a PDF and upload the file to your Github
repository. Give an account of the data structure in English as your answer to this question.  
This ERD has 3 entities: Customer, Product, and Orders. Each of these three have attributes listed. For Customer there are: CustId, FirstName, LastName, Street, City, State, Zipcode. For Product there are: ProductID, Color, Weight, Description. And for Orders, the intersection table, there are: OrderID, CustomerID, and ProductID.  

6. Consider the project you have chosen as a team. Draw a simple SADT (structured analysis and design
technique) diagram of the project. Create the drawing as a PDF and upload the file to your Github
repository. Explain your project on a high level in English as your answer to this question.  
The SADT for our project is centered around Online Banking, which evolved from our previous project of an ATM. The input is the customer data and banking information. The output is updated account information. The functionality provided is being able to deposit, withdraw, and transfer money as well as viewing the current balance. The controls are being able to login to your account and make modifications.  

7. This is not in the book. Consider the project you have chosen as a team. Draw a simple SDL
(Specification and Description Language) diagram of the project. Create the drawing as a PDF and
upload the file to your Github repository. Explain your project on a high level in English as your
answer to this question.  
This SDL has a Start process and from there the user logs in and can begin a transaction. The transaction can be either a deposit, withdrawl, transfer or viewing balance. After these the user has the ability to log out and end the process.  

8. Find an image or document online of a simple function using Z. Convert the image or document to a
PDF and upload it to your Github repository. Explain the specification in English as your answer to
this question. Note that the Z language is difficult and takes years to learn. This course is not a course
in Formal Methods, where you might spend an entire semester learning the Z language. You don't
have to understand the Z specification. All you have to do is have some faint idea about its concept
and operation.  
Z specification contains 4 main parts: sets, state definition, initial state and operations. In the example I found of a bank account for withdrawing money, there is the a BankAccount, dollarAmount and centAmount. The dollarAmount and centAmount are sets of all natural numbers. The Z language is used to write functions to maniuplate objects in the dollar and cent Amount sets.   

