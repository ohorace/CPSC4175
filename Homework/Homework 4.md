Olivia Horace  
Homework 4  
  
1. What is an entity class? A boundary class? A control class?  
An entity class models information that is more permanent, will be kept for a longer period of time.  
A boundary class models the interaction between software and actors, or things manipulating the software.  
Typically, boundary classes are associated with inputs and outputs.  
A control class models algorithms and computations.  
   
2. Write a use case pertaining to your project.  
Enter a customer username and password.  
  
3. Write a successful scenario pertaining to your project.  
1. Customer 1 enters username and password to log into online banking system.  
2. The login control searches for the entered username within the list of banking system users.  
3. When found, the login control matches the password entered to the password on file for said user.  
4. If the login is successful, the login control alerts the account management system that a user has been verified.  
5. The account management system displays account information as well as options for account transactions.  
  
4. Write an unsuccessful scenario pertaining to your project.  
1. Customer 1 enters username and password to log into online banking system.  
2. The login control searches for the entered username within the list of banking system users.  
3. When found, the login control matches the password entered to the password on file for said user.  
4. If the password does not match the password stored in the banking system’s database, then the user must re-enter their username and password.  
5. If, after a third unsuccessful attempt, the username and password cannot be verified then the user is prevented from making another login attempt.  
  
5. Using your answers to the three previous questions, use the noun extraction method to extract the
classes. If practicable, identify the classes you extract as entity, boundary, and control classes. If all
your classes are entity classes, you will not be able to do this.  
The Customer enters their username and password. The login control searches for the username, and if found, compares the password entered to the password that has been stored in the customer list. The login control will remain active until the Customer is either successfully authenticated or locked out due to numerous unsuccessful attempts.  
  
Nouns: customer, username, password, control, list, attempts  
Entity classes: Customer  
Boundary: Control  
Control: Attempts  