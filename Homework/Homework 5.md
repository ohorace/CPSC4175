## Olivia Horace  
## Homework 5  
  
1. What are the two basic ways of designing a product? Explain what they are and how they differ.  
The two basic ways of designing a product are operation-oriented design and data-oriented design. Operation-oriented design focuses on the operations. In other words, it is focused on making the modules of a project work together. Data-oriented design considers the data first. The data for the project is the main focus and then procedures are design based on that data.  
  
2. What are the inputs and the outputs to the design workflow, according to the book? Briefly explain
why the particular inputs are important and how they impact design. Briefly explain how the particular
outputs are important and how they influence design.  
The input to the design process is the specification document. The output is the design document. For input, the specification document describes what the product is expected to do. For output, the design document describes how the product is supposed to accomplish this.  
  
3. Traditionally, a computer program was seen as a data processing application. Variables were divided
into three categories: input variables, output variables, and processing variables. The book describes
a design process based on this paradigm that is recursive. Explain in detail how you would design
a student's graduation requirements in terms of input variables, output variables, and processing variables.
This is not asking for a design, but just identification of variables you might want to create and where
in the design you would place them.  
General design  
Input Variables:  
firstName – String  
lastName – String 
birthday – String   
studentID – int  
  
Processing variables:  
GPA – double  
coursesTaken – String[]  
major – String[]  
coursesRequired – String[]  
  
Output variables:  
expectedGraduation – String  
metRequirements – Boolean  
  
4. Perform a transaction analysis for the graduation requirements problem you used for the previous
question. Your answer should be a sequential list of subprocedures you would design to solve the
problem. Notice that the previous question called for what was, in essence, a list of nouns, while this
question calls for, in essence, a list of verbs.  
Enter student ID  
Verify student name and birthday  
Retrieve student major  
Retrieve courses required for major  
Retrieve courses taken by student  
Compare course taken to courses required  
Calculate number of courses remaining, if any  
Update metRequirements  
Determine expected graduation date  
  

5. Object-oriented analysis and design conceptually is seen as a grouping of objects, instantiated from
classes. Classes encapsulate both states (variables, nouns) and behavior (subprocedures, verbs). Based
on your answers to the two previous questions, describe one class that might be appropriate for a
graduation requirements application. Identify the attributes (properties) and behaviors (methods)
this class might contain.  
Student Class  
Properties:  firstName, lastName, birthday, studentID, expectedGraduation, GPA, major, coursesTaken, metRequirements  
Behaviors: Verify student name and birthday, compare courses taken to courses requirement for major, determine expected graduation date, calculate courses remaining, update metRequirements  
  
6. As discussed in the book, the design workflow can be considered an iterative, spiral process in itself.
As we have been discussing in class, the design phase can be seen as part of an iterative that also
includes analysis, implementation, and testing phases. The answer to this question obviously depends
on the nature of the software under development, so there is no one correct answer to this question.
Here is the question: Consider the software project you are working on for this class, and briefly state
which view you think is more appropriate to your work. Justify your answer by making a reasonable
argument as to why you answered this question the way you did.  
I think for our project, online banking, the approach of design being an iterative process within itself is more fitting. In our case, working on the design alone is almost a standalone phase of the project. Within the design process itself we ended up changing our entire project solely based on how we were designing our product. Although I understand where design fits in the grand scheme of software engineering, by itself it’s an entire process. In our case, our two design weeks have resulted in significant changes each time. Each of those changes led to us restarting our design process, or nearly restarting it, in each of our design weeks. 
  
7. What is the difference between testing an implementation and testing a design? Write a procedure
for testing the design of the student graduation requirements problem in the questions above. Define
a procedure for one of the following: either a data analysis design, a transaction analysis design, or an
object oriented design.  
Testing the design is verifying that the specifications have been translated corrected into the design. This kind of testing also makes sure the actual design is correct. Implementation testing is testing the actual code for the product making sure that it performs as expected.  
  
Testing design:  
Link the student’s major to the classes required for that major  
Be able to compare the courses the student has taken to the classes required  
Be able to determine the graduation date based on the number of courses left  
Determine if the requirements have been met to graduate  
  
Data Analysis Design:  
Verify data is formatted correctly as input  
Enter data  
Process data  
Output data  
Verify data is formatted correctly as output  
  
8. What is the cyclomatic complexity of figure 1? Explain your answer.  
The cyclomatic complexity of a design is the number of binary decisions plus 1 or the number of branches in the code. In figure 1, the cyclomatic complexity is 3. There are 2 binary decisions in the chart, plus 1, which is 3.  
  
9. Discuss one CASE tool you have previously used. If you have never used a CASE tool, find an
open source CASE tool using an internet search, download and install it, complete a \Hello World"
application, and discuss your experience.  
I downloaded a free trial of MagicDraw. There’s a learning curve and it was kind of heard to use at first. I have never used any software like this before so I had to get used to navigating within the application. This software had some very basic features to help create diagrams. Although I couldn’t see myself using this kind of software on a regular basis, I do see its usefulness. It’s interesting because at my job I know a few developers and I haven’t heard them mention tools that they use for designs. I want to learn what kind of CASE tools are used by application developers at the company I work for.  
  
10. Read the article \the-right-stu_.pdf" in the pdf directory. (You may find a better copy online.) Write
a one paragraph appreciation of the article.  
I thought this article was very well written. It is so interesting that the code used to launch space shuttles only had 1 error in the last three versions. The average programs that length would have 5000 errors. It is so impressive for software, something man made, to be that close to being perfect. However, as noted in the article, the software had to be. Bill Pate was quoted as saying in the article that “[if] the software isn’t perfect, some of the people we go to meetings with might die”. I’m sure that is a tremendous amount of pressure on developers to know that they could be responsible for the death of crew members if something goes wrong.  Likewise, this article emphasized the importance of the software, not the hardware. The software is what ensures the proper operation of these shuttles in space.  

