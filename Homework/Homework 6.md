# Olivia Horace  
## Homework 06, CPSC-4175  
  
#### 1. Consider the programing languages you may have studied and their differences. Think of two problem domains you would use for each language. For each problem domain, explain why your choice of the other language would be a poorer choice for an implementation language. ####  
For designing a mobile application I would use Java. Java is an pbject oriented language and would be ideal for creating the modules needed for creating an application. A language like C wouldn't be as good for this because it is not object oriented so you would be limited in your design.  
On the other hand, creating a scheduler for an operating system would be better done in a language like C. When coding in C, you have more access to machine functions as well as handling memory. When I learned how to make a scheduler, it was taught using C. Although threading can be done with Java, operating system level designing is better handled by C and Java also has a slower runtime. Likewise, Java does not allow you to use pointers so you can only pass variables by reference.  
  
#### 2. Give some concrete counter-examples of good programming practices as discussed in the book. These include meaningful variable names, self documenting code, symbolic constants, and code layout. In other words, give examples of what not to do. ####  
Counter-examples:   
-Use variable names that are easy to remember and type: var1, var2  
-Include minimal comments for methods as well as complicated/complex algorithms  
-Heavily use constants to avoid repetitive variables  
-Don't include blank lines between functions...it makes programs longer and significantly increases the file size  
-Correctly documented, complex nested if statements are encouraged because they prevent the creation of new code blocks  
-Code standards are a guide, not an absolute law. Do what is best for your program  
  
#### 3. Give two versions of coding standards for subprocedure blocks. This may require an internet search. Which do you prefer, and why? ####   
Lab 400 has standards for subprocedures. An example of this is that the name of a subprocedure should be limited to 14 characters. However, it is suggested that longer (within the 14 character limit) the name is, the better.   
  
IT Jungle presents another coding standard that involves making subprocedures very short and to the point. They should only perform one task and should be thought of as standalone projects. I prefer this coding standard because it is how I have been taught to create subroutines. This also usually made it easier to find where my errors were in my programs.  
  
#### 4. An informal description of the DRY principle is this: "The second time you write exactly the same code, stop what you are doing and place that functionality in a subprocedure. Then, invoke the subprocedure whenever you need that functionality." Give one example of this from your previous
programming experience. If you have never experienced this in practice, make up an example. ####  
One assignment I was given in CPSC 1302 was a Zoo database where I had to keep track of animals, how many of each animal there was, how much each animal ate, how much each animal weighed, etc. Even though we read the data from a text file and wrote it back out to a text file, I wanted to format my text in a special way. However, I was doing this for every array of animal types that I had. So finally, I made a static helper method in my main class to format and print my output.  
  
#### 5. What is a stub? What is a driver? Have you ever used stubs or drivers in your previous programming experience? If so, give an example. If not, consider a function that takes a unit price, a sales tax rate, and the quantity ordered, and write a stub (using pseudo code or a language of your choice) that takes these three arguments and returns a value. ####  
A stub is an empty artifact. A driver is a code artifact that calls another artifact one or more times to check the values returned during testing. I believe I have used a stub before. We were taught to use print lines to debug codes. So sometimes, I'll have a line or variable printed in the middle of my program to indicate how far it runs before something fails to execute. I use drivers to run programs and check to see if the values of my variables and/or objects are updating correctly.  
  
#### 6. List two strengths and one weakness of top down integration. ####  
One strength of top-down integration is fault isolation. It's easier to pinpoint from where an error comes. Another strength is that most major design flaws will be found early on. However, in order for this to be true, logic artifacts, which incorporate the decision-making flow of control aspects of the product, are coded and tested first. Then operational artifacts, which actually perform the operations of the product, are coded and tested.
  
A weakness is that artifacts that may be reused and could end up not being properly tested. It can be incorrectly assumed that an artifact is correct and it is just reused in its current state.  
  
#### 7. List two strengths and one weakness of bottom up integration. ####  
One strength of bottom-up integration is that operational artifacts are thoroughly tested in this approach. Another strength is that testing is completed with the use of drivers which have been defensively programmed.  
  
A weakness of this approach is that design faults are detected late, much later than in top-down. Since the logic artifacts are implemented last, if there is a major design fault, then it won't be detected until the end of the implementation phase.  
  
#### 8. This is not in the book and will require some independent research. A domain specific language (DSL) is a small, incomplete language typically use as a \glue" language between a lower level language (like C) and a higher level language (like Python). An example of a DSL might be a helper language for HTML, e.g. div(...) might resolve to <div> ...</div>. How might a DSL promote what the book calls sandwich integration? This is not a trick question but it will require some thought. If you work as a developer, you will eventually write your own DSLs for various purposes. ####  
DSLs are small languages that are specific to a particular aspect of a software system. A DSL can be either internal or external. Internal DSLs are a form of API in a host language. External DSLs are independent from the host language. Sandwich integration involves integrating code using both the top-down and bottom-up approaches. I suppose that DSLs could be used to tackle the issue of code integration and implementation from different angles.  
  
#### 9. What is the difference in testing carried out by the implementation group and the testing carried out by the SQA group? ####  
Testing carried out by the implementation group can sometimes be less thorough. Because the people testing the product already have in-depth knowledge of the program and what it is does, the testing maybe lackluster and miss defects. This is quite the opposite when compared to SQA testing, as they usually have no knowledge of the "inside" of a product. Likewise, SQA has the burden of making sure that products are thoroughly tested and SQA has more to lose if integration testing is performed improperly.  
  
#### 10. Read the letter by Edgar Dijkstra to the Communications of the ACM (in the PDF directory as dijkstra68.pdf) and write a one paragraph appreciation of this letter. ####  
This article definitely took some effort and patience to read. However, I especially liked the part where he talked about the programmer's process of making something is the true subject matter of his work as opposed to the end product. Creating software is really a process and I agree that the end product really isn't the most important part. Although, this is what people want to see, and could be the difference between having a job and getting fired, it is more than that. Ultimately, it is a craft, a skill, and the journey to get to the end is aspiring. He goes on to talk specifically about statements and conditions. In particular, he discusses the 'Go To' statement which can potentially be dangerous. Its use can make it hard to describe the process progress. For the most part, I was able to get some lessons out of this article, much of it went over my head however. I'm definitely able to appreciate development being regarded as a process. 

